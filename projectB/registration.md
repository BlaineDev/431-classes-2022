# Project B Registration Status

Last update: 2022-11-14 1:00 PM

## If you are using NHANES data in your project B, here's how I'd like you to describe the source of your data as part of your codebook in Study 1 and Study 2.

The NHANES dataset combines interviews and physical examinations from adults and children in the United States using surveys examining a nationally representative sample of about 5,000 persons each year. In (my/our) work, we used data from the 2017 - March 2020 survey period, and from the following data sets: Demographics (P-DEMO), and [list next data source, with P-XXXX name], and [list next data source, with P-XXXX name]. [If appropriate, you should then specify any restrictions on your data, perhaps to adults (specify your age range, which is usually 21-79 - do not use the 80-year old subjects) and/or people with a particular condition.)] 

## There will be nine teams of two investigators

### NHANES Projects

Form done by | Partner | Data Source | Study 2 <br /> Outcome | Study 2 <br /> *n* | Status
:-----------------: | :---------------: | :-------------------: | :-----------------: | ---: | :---:
Moein <br /> Amin | Karlo <br /> Toljan | NHANES | Triglyceride (mg/dl) <br /> `LBXTR` from `P_TRIGLY` | 3331 | Accepted. See [note](#note).
Chris <br /> Benson | Lent <br /> Mantshonyane | NHANES | Total cholesterol (mg/dl) <br /> `LBXTC` from `P_TCHOL` | revise | Email sent 11/14.
Shubho <br /> Das | Toby <br /> Jin | NHANES |  LDL-Cholesterol, Friedewald (mg/dL) <br /> `LBDLDL` from `P_TRIGLY` | revise | Email sent 11/14.
Alex <br /> Gurgis | Tarek <br /> ElShebiny | NHANES | Body-mass index (kg/m^2) <br /> `BMXBMI` from `P_BMX` | 1163 | Accepted. See [note](#note).
Sahana <br /> Kannan | Sajan <br /> Patel | NHANES | **Times broken/fractured wrist** | **4987?** | **Yes**
Lydia <br /> Masar | Shwetank <br /> Singh | NHANES | **Self-reported weight** | 6364 | **Yes**
Fang <br /> Wang | Tian <br /> Liu | NHANES | Direct HDL cholesterol (mg/dl) | 1752
Savannah <br /> Wu | Qihao <br /> Zhang | NHANES | **Self-reported Systolic BP** | 817 | **Yes**

#### Notes

1. Be sure you restrict your sample to adults ages 21-79. That should be accomplished with a simple filter immediately after you ingest the data.
2. If the variable name and data set name Dr. Love has listed above doesn't match your plans, contact him via email immediately.
3. In your codebook, start with this statement (filling in your pieces as appropriate):

> The NHANES dataset combines interviews and physical examinations from adults and children in the United States using surveys examining a nationally representative sample of about 5,000 persons each year. In (my/our) work, we used data from the 2017 - March 2020 survey period, and from the following data sets: Demographics (P-DEMO), and [list next data source, with P-XXXX name], and [list next data source, with P-XXXX name]. [If appropriate, you should then specify any restrictions on your data, perhaps to adults (specify your age range, which is usually 21-79 - do not use the 80-year old subjects) and/or people with a particular condition.)] 


### Non-NHANES Projects

Form done by | Partner | Data Source | Study 2 <br /> Outcome | Study 2 <br /> *n* | Status
:-----------------: | :---------------: | :-------------------: | :-----------------: | ---: | :---:
Millie Zhou | Naji Ayyash | [NFL data from Advanced Sports Analytics](https://www.advancedsportsanalytics.com/nfl-raw-data) |  Total Fantasy points | 9992

## So, far, I know about these 40 individual projects

Investigator | Data Source | Study 2 Outcome | Study 2 *n* | Revision Requested?
:-----------------: | :-------------------: | :-----------------: | ---: | :---:
Bryan Abadie | NHANES | Serum triglyceride (mg/dl) | 4518 
Samer Alanazi | NHANES | **Needs to be re-specified** | 7029 | **Yes**
Samantha Baker | NHANES | Direct HDL cholesterol (mg/dl) | 653
Jules Joel Bakhos | NHANES | Total Spine Bone Density | **2121?** | **Yes**
Sarah Barker | NHANES | Blood lead level (ug/dl) | 1322
Seth Bauer | [MIMIC-II](https://physionet.org/content/mimic2-iaccd/1.0/) | Heart Rate at ICU admission | 1758
Lithe Basbous | NHANES | Direct LDL cholesterol (mg/dl) | **not specified** | **Yes**
Alison Berry | NHANES | **Needs to be re-specified** | **redo** | **Yes**
Yinglun Geng | NHANES | **Needs to be re-specified** | **redo** | **Yes**
Izzy Genuario | NHANES | Total cholesterol (mg/dl) | 897
Pedram Golnari | NHANES | Serum triglyceride (mg/dl) | 3901 
Sarah Grabinski | [Shen et al. paper](https://datadryad.org/stash/dataset/doi:10.5061%2Fdryad.pd44k8r) | **needs a new outcome** | **redo** | **Yes**
Katie Hassett | NHANES | Body-mass index (kg/m^2) | 5540
Benjamin Heifetz | [Kaggle Stroke Prediction Data](https://www.kaggle.com/datasets/fedesoriano/stroke-prediction-dataset) | Body-mass index (kg/m^2) | 3426 
Madi Hunt | NHANES | Glycohemoglobin (%) | 6064
Naveen Kannan | NHANES | Direct HDL cholesterol (mg/dl) | 2809
Rupleen Kaur | NHANES | **Needs to be re-specified** | **redo** | **Yes**
Aqsa Khan | NHANES | Systolic BP (1st reading - mm Hg) | 1839
Dan Kingsley | NHANES | Total white blood cell count | 3264
Beverly Koepf | [Lost, found adoptable pets](https://catalog.data.gov/dataset/lost-found-adoptable-pets) | **not going to work** | **redo** | **Yes**
Keisi Kotobelli | NHANES | Systolic BP (1st reading - mm Hg) | 7187
Valeria Martinez | NHANES | Most recent A1c level (%) | 530
Marie Masotya | NHANES | Total cholesterol (mg/dl) | 1161
Sarah McNeer | [Vital Statistics Birth Data](https://www.nber.org/research/data/vital-statistics-natality-birth-data) | Gestational age (weeks) | 9421
Sid Mittal | [Health Information National Trends Survey](https://hints.cancer.gov/data/download-data.aspx) | Average time doing moderate exercise | 884
Ben Mittman | NHANES | Body-mass index (kg/m^2) | 6121
Hala Nas | NHANES | Median liver stiffness (kilopascals) | 9700
Anya Nazarenko | NHANES | Total cholesterol (mg/dl) | 5210
An Nguyen | NHANES | Body weight (BMXWT) | 2513
Anthony Orsino | [National Health Interview Series](https://healthsurveys.ipums.org) | Family Income as % of Poverty | 1969
Sameer Prasada | NHANES | Direct LDL cholesterol (mg/dl) | 3277
Kim Robbins | NHANES | Total cholesterol (mg/dl) | 1293
Sam Rodgers-Melnick | [National Health Interview Survey 2019](https://www.cdc.gov/nchs/nhis/2019nhis.htm) | PHQ Depression Score | 6003
Miza Salim Hammoud | NHANES | Body-mass index (kg/m^2) | 6699
Hossam Sarhan | NHANES | Total femur bone mineral density | 3545
Faruk Senturk | NHANES | Liver steatosis level (db/m) | 2590
Neha Solanki | NHANES | **Needs to be re-specified** | **redo** | **Yes**
Xinyu Sun | NHANES | Body-mass index (kg/m^2) | 7352
Max Tjen | NHANES | Friedewald LDL cholesterol estimate (mg/dl) | 2597
Meredith Zhang | NHANES | Current body weight | 5208
