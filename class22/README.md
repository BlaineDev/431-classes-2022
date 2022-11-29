# 431 Class 22: 2022-11-29

[Main Website](https://thomaselove.github.io/431-2022/) | [Calendar](https://thomaselove.github.io/431-2022/calendar.html) | [Syllabus](https://thomaselove.github.io/431-syllabus-2022/) | [Notes](https://thomaselove.github.io/431-notes/) | [Contact Us](https://thomaselove.github.io/431-2022/contact.html) | [Canvas](https://canvas.case.edu) | [Data and Code](https://github.com/THOMASELOVE/431-data)
:-----------: | :--------------: | :----------: | :---------: | :-------------: | :-----------: | :------------:
for everything | for deadlines | expectations | from Dr. Love | ways to get help | lab submission | for downloads

## Today's Slides

Class | Date | Reveal JS (HTML) | Quarto .qmd | PDF file | Recording
:---: | :--------: | :------: | :------: | :--------: | :-------------:
22 | 2022-11-29 | **[Slides 22](https://thomaselove.github.io/431-slides-2022/class22.html)** | [Code 22](https://thomaselove.github.io/431-slides-2022/class22.qmd) | [PDF 22](431%20Class%2022.pdf) | Visit [Canvas](https://canvas.case.edu/), select **Zoom** and **Cloud Recordings**

![](https://github.com/THOMASELOVE/431-classes-2022/blob/main/class22/Vickers_2022-11-14.png) from [Twitter](https://twitter.com/vickersbiostats/status/1592129524426485760)

## Announcements

1. Lab 6 Grades and Feedback are now available on the [Course Grades Roster](https://bit.ly/431-grades-2022).
2. Three nice essays from Question 6 in Lab 6 are posted to [our Shared Drive](https://docs.google.com/document/d/1aqcxNcmUy1BTdV5a3Ocvbgau2aJshX9DCl_l5siPe_I/edit?usp=share_link).
3. The Answer Sketch and Grading Rubric for Lab 7 are now available on our Shared Drive.
4. A few of you have yet to read carefully [the instructions for Project B](https://thomaselove.github.io/431-projectB-2022/), in particular the very important [Checklist](https://thomaselove.github.io/431-projectB-2022/checklist.html).
5. Remember that we will not have class on Thursday 2022-12-01. 
    - Instead, I will hold a Zoom-only **Ask Me Anything** session from 1:00 to 2:00 PM on Thursday 2022-12-01, which appears in the regular Zoom section of [Canvas](https://canvas.case.edu) and in an email I sent to you on Monday 2022-11-28. 
    - I will record the Ask Me Anything session and make it available to you all, so you don't have to join if you don't have any questions of your own to ask.
6. Zoom information for the Project B presentations is now available in the Announcements section of [Canvas](https://canvas.case.edu/). The Project B [schedule of presentations is here](https://github.com/THOMASELOVE/431-classes-2022/blob/main/projectB/schedule.md).
7. Quiz 2 is [now available](https://github.com/THOMASELOVE/431-quizzes-2022/tree/main/quiz2), and is due next Monday 2022-12-05 at 9 PM.

## References Related to Today's Class

Some of today's slides were originally planned for Class 21. I've left the old Class 21 slides as they were, and modified here only.

- Ronald L. Wasserstein, Allen L. Schirm & Nicole A. Lazar (2019) [Moving to a World Beyond "p < 0.05"](https://www.tandfonline.com/doi/full/10.1080/00031305.2019.1583913), *The American Statistician*, 73:sup1, 1-19, DOI: [10.1080/00031305.2019.1583913](https://doi.org/10.1080/00031305.2019.1583913). 
    - Ron gave a [one-hour talk you can watch here](https://t.co/GbQF01h4jU) on "[Helping to move to a world beyond p < 0.05](https://t.co/GbQF01h4jU)" which I cannot recommend enough.
- Ronald L. Wasserstein & Nicole A. Lazar (2016) [The ASA's Statement on p-Values: Context, Process, and Purpose](https://www.tandfonline.com/doi/full/10.1080/00031305.2016.1154108), *The American Statistician*, 70:2, 129-133, DOI:
[10.1080/00031305.2016.1154108](https://doi.org/10.1080/00031305.2016.1154108).
- [The Growing Importance of Reproducibility and Responsible Workflow in the Data Science and Statistics Curriculum](https://www.tandfonline.com/doi/full/10.1080/26939169.2022.2141001) by Nicholas J. Horton, Rohan Alexander, Micaela Parker, Aneta Piekut & Colin Rundel (2022) *Journal of Statistics and Data Science Education*, 30:3, 207-208, DOI: 10.1080/26939169.2022.2141001

Some other resources for learning more after today's talk are:

- Frank E. Harrell's [A Litany of Problems with *p*-values](https://www.fharrell.com/post/pval-litany/) blog post most recently updated in 2020.
- William Briggs' [Everything Wrong with P-values Under One Roof](http://wmbriggs.com/post/26125/) which links to a detailed article on the subject.
- Jeffrey Leek and Roger Peng [P-values are just the tip of the iceberg](references/Leek_and_Peng_2015_Pvalues_Nature.pdf)
- Jeffrey D Blume, Lucy D'Agostino McGowan, William D. Dupont, Robert A Greevy [Second-generation p values: Improved rigor, reproducibility and transparency in statistical analyses](references/Blume_etal_2018_Second_Generation_P_Values.pdf)
- Andrew Gelman and John Carlin [Beyond Power Calculations: Assessing Type S (Sign) and Type M (Magnitude) Errors](references/Gelman_Carlin_2014_Beyond_Power_Calculations.pdf)
- [Scientists rise up against statistical significance](https://www.nature.com/articles/d41586-019-00857-9) in *Nature* 2019-03-20
- [It's time to talk about ditching statistical significance](https://www.nature.com/articles/d41586-019-00874-8) also in *Nature* 2019-03-19.
- Briggs, William M., 2019. [Everything Wrong with P-Values Under One Roof](http://wmbriggs.com/post/26125/). In Beyond Traditional Probabilistic Methods in Economics, V Kreinovich, NN Thach, ND Trung, DV Thanh (eds.), pp 22–44. DOI 978-3-030-04200-4_2
- the "PROBABLE CAUSE" graphic reprinted in this [Nature piece by Regina Nuzzo](https://www.nature.com/news/scientific-method-statistical-errors-1.14700), originally from T. Sellke et al. in *The American Statistician*, 2001.
- and several great pieces by Christie Aschwanden at 538:
    - "[Not Even Scientists Can Easily Explain P-Values](https://fivethirtyeight.com/features/not-even-scientists-can-easily-explain-p-values/)", and
    - "[Statisticians Found One Thing They Can Agree On: It's Time To Stop Misusing P-values](https://fivethirtyeight.com/features/statisticians-found-one-thing-they-can-agree-on-its-time-to-stop-misusing-p-values/)", and
    - "[Science Isn't Broken](https://fivethirtyeight.com/features/science-isnt-broken/#part1)" with graphics by Ritchie King.
- You may also be interested in this piece at pbs.org about a NOVA program entitled "[Rethinking Science's Magic Number](https://www.pbs.org/wgbh/nova/article/rethinking-sciences-magic-number/)".
- I have given several talks on "Rethinking Statistical Significance" in recent years. The Github repository (90 minutes at MetroHealth Medical Center and the Center for Health Care Research and Policy, with an audio recording) is at https://github.com/THOMASELOVE/rethink, if you're a glutton for punishment.
- [Why p values are like puppies](https://www.youtube.com/watch?v=9jW9G8MO4PQ) is a 3:29 YouTube Video by Cassie Kozyrkov, MS, Chief Decision Scientist, Google Inc. It explains how to understand and interpret *p* values in an intuitive way using an example based on puppies.

## Remaining Deadlines

1. Our second and final Quiz is [now available](https://github.com/THOMASELOVE/431-quizzes-2022/tree/main/quiz2). The Quiz is due on Monday 2022-12-05 at 9 PM.
2. We will have a Minute Paper after Class 23 due Wednesday 2022-12-07, but there is no minute paper this week.
3. Those of you who are in any way disappointed with your grade in the course so far, **or** who are looking to continue working in or studying statistics and data science past the 431-432 sequence, should definitely be working on [Lab X](https://github.com/THOMASELOVE/431-labs-2022/blob/main/labX.md), which is due Monday 2022-12-12 at Noon.
4. Should you want Dr. Love to regrade one (or more) of Labs 1-7, please be sure to fill out the [Lab Regrade Request Form](https://bit.ly/431-2022-lab-regrade-requests), which is also due Monday 2022-12-12 at Noon.
5. Project B presentations will be held on December 8, 12, 13 and 15 according to [the schedule posted here](https://github.com/THOMASELOVE/431-classes-2022/blob/main/projectB/schedule.md). 
    - Zoom information for the Project B presentations is now available in the Announcements section of [Canvas](https://canvas.case.edu/).
    - Read [the Checklist](https://thomaselove.github.io/431-projectB-2022/checklist.html) well in advance to make sure you complete everything you need to do and are prepared for this Oral Presentation of Results properly.
6. The Project B final reports for [Study 1](https://thomaselove.github.io/431-projectB-2022/study1b.html) and for [Study 2](https://thomaselove.github.io/431-projectB-2022/study2b.html) and the [self-evaluation form](https://bit.ly/431-2022-projectB-self-evaluation) are due at noon on Monday 2022-12-19. Read [the Checklist](https://thomaselove.github.io/431-projectB-2022/checklist.html) well in advance to make sure you complete everything you need to do.
    - You should submit both your [Study 1 report](https://thomaselove.github.io/431-projectB-2022/study1b.html) (Rmd and HTML) and your [Study 2 report](https://thomaselove.github.io/431-projectB-2022/study2b.html) (Rmd and HTML) - so a total of four documents to Canvas by that time. 
    - If you are working with a partner, exactly one of you should submit these four items. The other person should submit a one-page note to Canvas (word or PDF is best) containing your name, and stating something like “I worked on Project B with [your partner’s name] and they will submit Project B for our group.”
    - If you are working with data other than NHANES data, you will also submit your data.
    - The [Self-Evaluation for Project B Form](https://bit.ly/431-2022-projectB-self-evaluation) should take about 15 minutes to complete. If you are working in a team, each of you need to complete the form as an individual. The Form should be completed after meeting with Dr. Love for your presentation **and** after submitting your final reports to Canvas.

## One Last Thing

[Raincloud Plots with ggplot2](https://z3tt.github.io/Rainclouds/) by Cédric Scherer demonstrates many nice approaches to showing the distributions of data batches, beyond what you can get from a boxplot-violin combination. Lots of good choices to consider here when displaying data in Project B.



