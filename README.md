# D206-WGU-school-project
Used R to clean data with Fake Medical Data

Scenario: Medical Readmission
In the medical industry, readmission of patients is such a problem that an external organization penalizes hospitals for excessive readmissions (Centers for Medicare and Medicaid Services or CMS). When it comes to readmission penalties, studies show that many hospitals are overconfident and underprepared. The percentage of hospitals penalized for readmissions has increased each year since CMS began imposing penalties, and according to the CMS reporting, as much as 78 percent of hospitals were fined in fiscal year 2015. However, three-quarters of hospitals feel confident in their ability to reduce readmissions, and only 55 percent of them anticipate receiving a penalty this year. Given the historical trend and the addition of COPD and Hip & Knee replacement to the list of medical conditions measured, the percentage of hospitals penalized will likely be much higher than 55 percent. Additionally, although hospitals are applying various reduction strategies, fewer than 1 in 5 utilize technology that is specific to reducing their readmissions, so they may not be doing all that they can.
You are an analyst on a team of analysts for a popular medical hospital chain with patients in almost every state in the United States.
Note: The original reason for hospitalization is not provided in the data. The purpose of cleaning the raw data is to prepare the data for analysis. The analysis is used to predict readmission based on other conditions and factors of the patient.
Data File being used:
medical_raw_data.csv
Data
Dictionary:
The data set includes the following information:
• patients who are readmitted to the hospital within a month of release (the “ReAdmis” column) • patient medical conditions (high blood pressure, stroke, obesity, arthritis, diabetes, etc.) • patient information (service they received while hospitalized, days in hospital, type of initial admission, etc.)  patient d emographic info rmation gender, age, job, education level, etc
The data set consists of 10,000 customers and 5 0 columns/ variables:
CaseOrder: A placeholder variable to preserve the original order of the raw data file
C ustomer _id Unique patient ID

Interaction UID Unique IDs related to patient transactions procedures and
admissions
The
following variables represent customer demographic data:
o
City Patient city of residence as listed on the billing statement
o
State Patient state of residence as listed on the billing statement
Services Primary service the patient received while hospitalized b lood work,
intravenous, CT scan, MRI

Initial_ d ays The n umber of days the patient stayed in the hospital during the initial
visit
TotalCharge The amount charged to the patient daily This value reflects an average
per patient based on the total charge divided by the number of days hospitalized This
amount reflects the typical charges billed to patient s not including specialized
treatments.
Additional_ c harges The average amount charged to the patient for miscellaneous
procedures, treatments, medicines, anesthesiology, etc
The following variables represent responses to an eight question survey asking customers
to rate the importance of various factors/surfaces on a scale of 1 to 8 (1 most important,
8 least important)

Item1: Timely admission
Item2: Timely treatment
Item3: Timely visits
Item4: Reliability
Item5: Options
Item6: Hours of treatment
Item7: Courteous staff
Item8: Evidence of active listening from doctor
