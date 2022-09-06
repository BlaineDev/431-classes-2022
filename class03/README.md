# 431 Class 03: 2022-09-06

[Main Website](https://thomaselove.github.io/431-2022/) | [Calendar](https://thomaselove.github.io/431-2022/calendar.html) | [Syllabus](https://thomaselove.github.io/431-syllabus-2022/) | [Notes](https://thomaselove.github.io/431-notes/) | [Contact Us](https://thomaselove.github.io/431-2022/contact.html) | [Canvas](https://canvas.case.edu) | [Data and Code](https://github.com/THOMASELOVE/431-data)
:-----------: | :--------------: | :----------: | :---------: | :-------------: | :-----------: | :------------:
for everything | for deadlines | expectations | from Dr. Love | ways to get help | lab submission | for downloads

## Today's Slides

Class | HTML Link to Slides | Date | Quarto file (download)
:---: | :------------: | :---: | :--------------:
03 | [Slides for Class 03](https://thomaselove.github.io/431-slides-2022/class03.html) | 2022-09-06 | [Quarto for Class 03 slides](https://thomaselove.github.io/431-slides-2022/class03.qmd)

### Extra Materials for Class 03 found in the [data folder](https://github.com/THOMASELOVE/431-classes-2022/tree/main/class03/data)

These items are also part of the newly revised [431-data page](https://github.com/THOMASELOVE/431-data).

- [431-first-r-template.Rmd](data/431-first-r-template.Rmd) is the **template** I will start with in developing today's materials.
- [431-class03-all-code.Rmd](data/431-class03-all-code.Rmd) is a revision of the template that includes all of the code I will develop today in [the slides](https://thomaselove.github.io/431-slides-2022/class03.html).
- [quick_survey_2022.csv](data/quick_survey_2022.csv) contains the data from our [Quick Survey in Class 02 (pdf)](https://github.com/THOMASELOVE/431-classes-2022/blob/main/class02/431_surveyhandout_2022-09-01.pdf) for you and for students in the 2014-2021 versions of 431.

### Analytic Questions We'll Address Today

1. What is the distribution of pulse rates among students in 431 since 2014?
2. Does the distribution of student heights change materially over time?
3. Is a Normal distribution a good model for our data?
4. Do taller people appear to have paid less for their most recent haircut?
5. Do students have a more substantial tobacco history if they prefer to speak English or a language other than English?

### R Tools We'll Demonstrate Using Today's Materials

In addition to demonstrating general approaches for creating R projects and R Markdown files, and loading R packages, we'll demonstrate most (if not quite all) of the following key ideas...

1. Ingesting data with `read_csv` from a csv (comma-separated version text) file to create a tibble (data frame.)
2. Six key verbs from the `tidyverse`: `count`, `filter`, `select`, `mutate`, `group_by` and `summarize`
3. Using the pipe: `|>` to push information through a pipeline.
4. Using the assignment operator `<-` to assign results to a variable or tibble or other sort of object.
5. Summarizing data with `summary`, `tabyl` and with `mosaic::favstats`
6. Dealing with missing data via the creation of complete-case analyses with `filter(complete.cases(.))`
7. Converting categorical variables to factors with `as_factor`, and recoding the levels of those factors with `fct_recode`
8. Building plots using `ggplot` and the `ggplot2` package
    - Setting the x and y variables with `aes()`
    - Using `geom_histogram()` to obtain histograms of quantities
    - Using `geom_boxplot()` and `geom_violin()` for comparisons of quantities across categories (groups)
    - Using `geom_point()` and `geom_smooth()` to build scatterplots of the association between quantities and fit linear models and loess smooths to data
    - Building multiple plots with `facet_grid()` and `facet_wrap()` and by using `aes(group = ., color = .)` to divide plots by a category
    - Using `labs()` to set axis labels, main and sub-titles
    - Using `guides(col = "none")` to delete legends from a plot where color is used to separate groups
9. Using `lm` to fit and `summary(lm())` to summarize a straight-line ordinary least squares linear regression model
10. Using `sessionInfo()` to describe information about your installation of R at the end of your session.

All of this material is also demonstrated in early Chapters of the [Course Notes](https://thomaselove.github.io/431-notes/), and we will review (and augment) these ideas in class over the next few weeks.

## Announcements
 
1. There is a [Minute Paper after Class 03](https://bit.ly/431-2022-min-03), which you need to complete by NOON Wednesday 2022-09-07. A Minute Paper is a short survey (completed using a Google Form) where you will answer a few questions about how the course is going for you.
    - You'll need to be logged into Google via CWRU to complete the Minute Papers. 
    - **Always** complete the Minute Paper even if you weren’t able to attend the most recent class. 
    - More on the Minute Papers [here](https://github.com/THOMASELOVE/431-minute-2022), and [in the Syllabus](https://thomaselove.github.io/431-syllabus-2022/assignments.html#minute-papers).

2. If you’ve spent 15 minutes working on something and are stuck, don’t keep working on it. Step away for a while, and if you return and are still stuck, **ASK FOR HELP**.
    - Use our [Campuswire discussion board](https://campuswire.com/) to ask (and answer) questions about the course. Open 24 hours a day, 7 days a week.
    - Attend [TA office hours](https://thomaselove.github.io/431-2022/contact.html) (which began today at noon) to get one-on-one help or share a computer problem. Our Shared Google Drive (431 Fall 2022 Dr Love and Students) now contains Zoom links for TA office hours in a document called TA office hours schedule and Zoom links. No appointment is necessary. Please just drop in.
    - Professor Love will also hold "drop-in" office hours before and after each class.
    - Email Professor Love if you have any questions you don't feel comfortable asking in TA office hours or via Campuswire.

3. I continue to threaten to show a [video from Hans Rosling](https://www.gapminder.org/fw/world-health-chart/). Today, I expect to do just that. 
    - The updated [World Health Chart from Gapminder](https://www.gapminder.org/fw/world-health-chart/) may be of particular interest, and includes links to the [original video](https://www.youtube.com/watch?v=jbkSRLYSojo&feature=emb_imp_woyt) I planned to show to you, and the shorter update I will show today.
    - Some related thoughts, plots and links to data can be found in [Health, Wealth and Education: Is There a Link for Countries?](https://www.stlouisfed.org/open-vault/2021/july/health-wealth-education-link-countries) posted in July 2021 by Heather Hennerich.

4. Now is the time (if you haven't already) to [get started on Lab 01](https://github.com/THOMASELOVE/431-labs-2022), which is due Monday 2022-09-12 at 9 PM. 
    - While you don't need to develop an R Markdown file for Lab 01, you do need to use R and R Studio a bit.
    - You also need to have read the introduction to Spiegelhalter.

5. **Updates**
    - The [431 Packages list](https://github.com/THOMASELOVE/431-packages) has been updated to include [the gtExtras package](https://jthomasmock.github.io/gtExtras/).
    - The [431 Data page](https://github.com/THOMASELOVE/431-data) has been updated to include materials for today's class.

## 10 Interesting/Fun Facts about you, from the [Welcome to 431 Survey](https://bit.ly/431-2022-welcome-survey).

- I am a former pianist turned programmer.
- I am a board-certified music therapist.
- I have cycled across the state of Ohio seven times.
- I am a certified scuba diver.
- I am a gourmet pancake maker.
- I am a quadruplet. Fraternal. 
- I have played in the Little Italy Summer Bocce league.
- I am afraid of dogs.
- I enjoy knitting and spinning yarn.
- I grew up in Idaho and love anything outdoors.

## What Should I Be Working On?

1. The [Minute Paper after Class 03](https://bit.ly/431-2022-min-03), which is due at noon Wednesday 2022-09-07.
2. Get R and R Studio up and running effectively, if you haven't done so already.
3. Read through Chapter 1 of Spiegelhalter's *The Art of Statistics*.
4. Complete [Lab 01](https://github.com/THOMASELOVE/431-labs-2022) by its deadline: Monday 2022-09-12 at 9 PM.
5. If you've not already done so, complete [these Tasks we'd hoped you'd do last weekend](https://github.com/THOMASELOVE/431-classes-2022/tree/main/class02#things-to-do-this-weekend).

## One Last Thing

Thanks very much to those of you who completed the requirements of [Section 14 of the Syllabus](https://thomaselove.github.io/431-syllabus-2022/movies.html) on time, and thus received a little class participation credit. Opportunities like this will appear through the semester, so keep an eye out for them. 

In the meantime, those of you who didn't complete this task already, please do so today. Thanks!
