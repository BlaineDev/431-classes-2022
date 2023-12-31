# 431 Class 05: 2022-09-13

[Main Website](https://thomaselove.github.io/431-2022/) | [Calendar](https://thomaselove.github.io/431-2022/calendar.html) | [Syllabus](https://thomaselove.github.io/431-syllabus-2022/) | [Notes](https://thomaselove.github.io/431-notes/) | [Contact Us](https://thomaselove.github.io/431-2022/contact.html) | [Canvas](https://canvas.case.edu) | [Data and Code](https://github.com/THOMASELOVE/431-data)
:-----------: | :--------------: | :----------: | :---------: | :-------------: | :-----------: | :------------:
for everything | for deadlines | expectations | from Dr. Love | ways to get help | lab submission | for downloads

## Today's Slides

Class | Date | Reveal JS (HTML) | Quarto .qmd | PDF file | Recording
:---: | :--------: | :------: | :------: | :--------: | :-------------:
05 | 2022-09-13 | **[Slides 05 (& 06)](https://thomaselove.github.io/431-slides-2022/class05.html)** | [Code 05 (& 06)](https://thomaselove.github.io/431-slides-2022/class05.qmd) | [PDF 05 (& 06)](431%20Class%2005%20(and%2006).pdf) | Visit [Canvas](https://canvas.case.edu/), select **Zoom** and **Cloud Recordings**

- The **Reveal JS (HTML) Slides** link provides the version of the slides (in HTML) that I suggest you focus on during class.
- The Quarto file links provide the code I used (in [Quarto](https://quarto.org/)) to build the slides.
- The PDF file is a nearly-complete version of the posted HTML slides in a possibly more useful format. To print RevealJS slides to pdf from the HTML Link, [follow these instructions](https://quarto.org/docs/presentations/revealjs/presenting.html#print-to-pdf) using Google Chrome as your browser.

Note that today's slides are extra large, and will be used again in [Class 06](https://github.com/THOMASELOVE/431-classes-2022/tree/main/class06). The slides posted here and the slides posted for Class 06 were revised after Class 05 and are now identical, except for the date.

- Today's slides use some material from [Allison Horst's Stats Illustrations](https://github.com/allisonhorst/stats-illustrations).
- The `dm_431.csv` data are now available on our [431-data page](https://github.com/THOMASELOVE/431-data) and also in the [data folder for Class 05](https://github.com/THOMASELOVE/431-classes-2022/tree/main/class05/data)

## Resource of the Day

Chapter 3 on [Troubleshooting and asking for help](https://learnr.numbat.space/chapter3) from the good folks at [LearnR](https://learnr.numbat.space/) provides an interactive introduction to the topic. There's lots of great stuff at [LearnR](https://learnr.numbat.space/), including chapters on [data wrangling](https://learnr.numbat.space/chapter5), [data visualization](https://learnr.numbat.space/chapter6) and [linear regression](https://learnr.numbat.space/chapter7), as well as the basics of [R Markdown](https://learnr.numbat.space/chapter8). 

- I was alerted to this resource indirectly through [this tweet from Cynthia Huang](https://twitter.com/cynthiahqy/status/1559130278810886144?s=11&t=rxkhQ3svGtZ-SB_Qme248Q).

## Announcements

1. There is a [Minute Paper after Class 05](https://bit.ly/431-2022-min-05), which you'll need to complete by NOON Wednesday 2022-09-14.
2. An answer sketch (including grading rubric) for [Lab 01](https://github.com/THOMASELOVE/431-labs-2022#answer-sketches-and-grading-rubrics) is now available on our Shared Google Drive. 
    - Grades and the videos you developed for Question 1 should be available next Tuesday 2022-09-20.
3. Detailed instructions for [Project A](https://thomaselove.github.io/431-projectA-2022/) are [now available](https://thomaselove.github.io/431-projectA-2022/).
    - Project A is the first of two real data science projects you’ll be doing this semester. In Project A, you’ll each work with part of the [County Health Rankings 2022](https://www.countyhealthrankings.org/2022-measures) data. 
    - You can *and should* get started on the [Data and Proposal](https://thomaselove.github.io/431-projectA-2022/) materials now. All of that work can (and should, ideally) be completed in September. The [Analyses](https://thomaselove.github.io/431-projectA-2022/analyses.html) and [Final Report](https://thomaselove.github.io/431-projectA-2022/report.html) will be done in October.
    - Note that Dr. Love has provided you with several examples and tips, including a [Sample Proposal](https://thomaselove.github.io/431-projectA-2022/exampleA.html) to help you get started.
    - You can work alone, or with one other person on Project A. If you work as a pair, you create one project together, and each of you receive the same grade.
        - We'll set aside some time in Class 06 to let you chat with others and decide if you might like to work as partners.
4. Detailed instructions for [Project B](https://thomaselove.github.io/431-projectA-2022/) are also now available, but I wouldn't think about that now.
    - Project A is a September/October activity. Project B is a November/December activity.
5. We have updated the [Lab 02 instructions (fixing the hint)](https://github.com/THOMASELOVE/431-labs-2022).
6. We have updated the [templates for Labs 02 and 03](https://github.com/THOMASELOVE/431-data) as well as added some materials for sample projects A and B to the [431-data page](https://github.com/THOMASELOVE/431-data). Grab the latest version of the zip file at the [431-data page](https://github.com/THOMASELOVE/431-data) to avoid some confusion. 
7. **What does the tidyverse include?** 
    - The core packages in the `tidyverse` that load when you run `library(tidyverse)` are [`ggplot2`](https://ggplot2.tidyverse.org/), [`dplyr`](https://dplyr.tidyverse.org/), [`tidyr`](https://tidyr.tidyverse.org/), [`readr`](https://readr.tidyverse.org/), [`purrr`](https://purrr.tidyverse.org/), [`tibble`](https://tibble.tidyverse.org/), [`stringr`](https://stringr.tidyverse.org/) and [`forcats`](https://forcats.tidyverse.org/).
    - When you *install* the `tidyverse` package, that also installs many additional non-core packages that need to be loaded on their own. These include: [`readxl`](https://readxl.tidyverse.org/), [`googlesheets4`](https://googlesheets4.tidyverse.org/), [`haven`](https://haven.tidyverse.org/), [`lubridate`](https://lubridate.tidyverse.org/) (which is, I believe, about to move to the core group), [`magrittr`](https://magrittr.tidyverse.org/) and [`glue`](https://github.com/tidyverse/glue) plus many more packages that I don't think we'll use this term.
    - Visit [tidyverse.org](https://www.tidyverse.org/) and [R for Data Science](https://r4ds.hadley.nz/) for more details on the uses of these packages.
8. One last batch of a dozen interesting or fun facts that you included in the [Welcome to 431 Survey](https://bit.ly/431-2022-welcome-survey).
    - I love folklore/mythology/fairy tales, and SCUBA diving.
    - I love to drive to discount furniture stores.
    - I sang at the Sistine Chapel.
    - I used to be a firefighter and my spouse and I left our wedding in a fire engine.
    - I used to compete in national Yo-Yo competitions.
    - I'm an extra in a movie.
    - I'm a severe sleepwalker.
    - I love playing Ping-Pong.
    - My spouse and I met in college Marching Band.
    - I was awarded a scholarship to culinary school.
    - I went glass-bottom kayaking in the Florida Keys earlier this summer where I saw so much marine life and different varieties of plants and fish.
    - I started (and continue to run) a social media platform on Instagram and Tiktok to convey fast, easy, accurate, humble and free-of-charge medical information, speaking in Lebanese so it can be accessible for all the Arab world.

## What Should I Be Working On?

1. [Minute Paper after Class 05](https://bit.ly/431-2022-min-05) is due Wednesday 2022-09-14 at noon.
2. Read Spiegelhalter through Chapter 2, entitled "Summarizing and Communicating Numbers. Lots of Numbers."
3. Read through the [Project A instructions](https://thomaselove.github.io/431-projectA-2022/) and get started on selecting and cleaning your [Data](https://thomaselove.github.io/431-projectA-2022/data.html) so you can build your [Proposal](https://thomaselove.github.io/431-projectA-2022/proposal.html) in time for the early deadline on 2022-11-03 at noon you'll find in the [Calendar](https://thomaselove.github.io/431-2022/calendar.html).
4. This weekend would be a good time to [update your R packages](https://thomaselove.github.io/431-2022/software.html#updating-your-r-packages), and be sure you re-pull down the materials on our [431-data page](https://github.com/THOMASELOVE/431-data).

## One Last Thing

The FiveThirtyEight website has a lot of interesting data projects going on. Take a minute to look at "[60 Percent Of Americans Will Have An Election Denier On The Ballot This Fall](https://projects.fivethirtyeight.com/republicans-trump-election-fraud/)"
