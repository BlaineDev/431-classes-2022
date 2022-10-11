# 431 Class 13: 2022-10-11

[Main Website](https://thomaselove.github.io/431-2022/) | [Calendar](https://thomaselove.github.io/431-2022/calendar.html) | [Syllabus](https://thomaselove.github.io/431-syllabus-2022/) | [Notes](https://thomaselove.github.io/431-notes/) | [Contact Us](https://thomaselove.github.io/431-2022/contact.html) | [Canvas](https://canvas.case.edu) | [Data and Code](https://github.com/THOMASELOVE/431-data)
:-----------: | :--------------: | :----------: | :---------: | :-------------: | :-----------: | :------------:
for everything | for deadlines | expectations | from Dr. Love | ways to get help | lab submission | for downloads

## Today's Slides

Class | Date | Reveal JS (HTML) | Quarto .qmd | PDF file | Recording
:---: | :--------: | :------: | :------: | :--------: | :-------------:
13 | 2022-10-11 | **[Slides 13](https://thomaselove.github.io/431-slides-2022/class13.html)** | [Code 13](https://thomaselove.github.io/431-slides-2022/class13.qmd) | [PDF 13](431%20Class%2013.pdf) | Visit [Canvas](https://canvas.case.edu/), select **Zoom** and **Cloud Recordings**

## Announcements

1. Remember that we do not have class this Thursday 2022-10-13. Instead, you have a working day for your Project A proposal, which is due Friday 2022-10-14 at noon. Class 14 will be held on Tuesday 2022-10-18.
2. On 2022-10-07, I tweaked the Answer Sketch and Grading Rubric for [Lab 03](https://github.com/THOMASELOVE/431-labs-2022) on our Shared Drive to make the rubric match up better with the findings for Question 3.
3. Grades and Feedback on Lab 03 are now available on the [Course Grading Roster](https://bit.ly/431-grades-2022) on our Shared Drive.
4. I am moving the due date for [Lab 04](https://github.com/THOMASELOVE/431-labs-2022) back one week to Monday 2022-10-24 at 9 PM. We have already covered all of the material you need for Lab 04, but I wanted to give people a little more breathing room while working on Project A. Note that 2022-10-24 is part of the University's Fall Break.
5. Quiz 1 results and a full answer sketch should be available to you by Wednesday 2022-10-12 at 5 PM.
6. I have added chapters 29-31 to the [Course Notes](https://thomaselove.github.io/431-notes/) providing additional details on residual plots for regression assumptions, partitioning and evaluating models with training and test samples, and more on the Western Collaborative Group Study from Chapter 17 of the Notes.

## Proposal for Project A

Everyone who submitted an early [Proposal for Project A](https://thomaselove.github.io/431-projectA-2022/proposal.html) should have received feedback from me in email on Sunday 2022-10-09, and [the list is here](https://github.com/THOMASELOVE/431-classes-2022/blob/main/projectA/early_prop.md). A few tips for those of you working on this now:

- Dr. Love used [this list of 13 things we're looking for](https://thomaselove.github.io/431-projectA-2022/proposal.html#grading-the-proposal-13-things-were-looking-for) to develop his rubric. Items 8 and 9 were especially problematic for some reason, so look at those closely.
- Students who used the [Sample Project A Proposal](https://thomaselove.github.io/431-projectA-2022/exampleA.html) as a template, while removing the instructions that Dr. Love provided, produced relatively easy-to-work-with HTML files. That's important. Make it **easy for us to find your good work**!
- Review your HTML file closely to ensure that you have no unnecessary messages, warnings, or problems with your table of contents, headings, figures or tables, and that your codebook (which should include both a table of states and a table of variables, as I did in [the Demo Cookbook](https://thomaselove.github.io/431-projectA-2022/data.html#demo-codebook)) looks nice.
- Several people failed to tell us why they selected their states, or why they selected their variables, or at least neglected to put this information near the codebook where they were describing states and variables.
- Also in the codebook, be sure to provide understandable and clear descriptions of the units for each quantitative variable, and be sure to explicitly specify the roles for variables 1-5 (not just your outcome), as I did in [the Demo Cookbook](https://thomaselove.github.io/431-projectA-2022/data.html#demo-codebook). You should also specify the values for the splits (so, for instance, tell us what the median was if you split by the median) in your categorical variables.
- Run spell-check on your R Markdown file (by hitting the F7 key) before you knit the file to HTML, and be aware that the spell-check specifically does not check your section and subsection headings or your commented code.
- Use Campuswire and TA office hours to get help if you need it. This proposal submission should be clean.
- After the deadline (submit to Canvas before noon Friday), Dr. Love (and, perhaps, the TAs) will review your submissions quickly to ensure that your proposed plan meets the requirements for this project, and either approve the plan, or request changes. We hope to complete that work by Monday morning 2022-10-17. If changes are requested, you’ll have a very short time window (no more than 24 hours) to make those changes and resubmit until your plan is, eventually, approved, so please check your email on Monday the 17th.
    
## Today's Data

The source for today's data is [Saliva or Nasopharyngeal Swab Specimens for Detection of SARS-CoV-2](https://www.nejm.org/doi/full/10.1056/NEJMc2016359) by Anne L. Wyllie, et al. N Engl J Med 2020; 383:1283-1286 [DOI: 10.1056/NEJMc2016359](https://www.nejm.org/doi/full/10.1056/NEJMc2016359) (2020-09-24).

## What to Work On Before Our Next Class (Class 14: Tuesday 2022-10-18)

1. Your [Project A proposal](https://thomaselove.github.io/431-projectA-2022/proposal.html) (due Friday 2022-10-14 at **NOON** if you haven't already received an Accept from Dr. Love: See [list of accepted proposals](https://github.com/THOMASELOVE/431-classes-2022/blob/main/projectA/early_prop.md) here.)
2. Your [Project A analyses](https://thomaselove.github.io/431-projectA-2022/analyses.html) (if your proposal has been [Accepted by Dr. Love]((https://github.com/THOMASELOVE/431-classes-2022/blob/main/projectA/early_prop.md) here.)) - your [final Project A submission](https://thomaselove.github.io/431-projectA-2022/report.html) is due 2022-10-31 at 9 PM.
3. Read Spiegelhalter through Chapter 6 (Algorithms, Analytics and Precision).
4. [Lab 04](https://github.com/THOMASELOVE/431-labs-2022) is now due Monday 2022-10-24 (during Fall Break) at 9 PM, but you can do it today.

## Dr. Love is in a musical, "Something Rotten", which runs October 28 through November 19

[Details are here](https://github.com/THOMASELOVE/theater#theater) and I've been told the show may eventually sell out. A recent update is that masks will **not** be required in the audience.

