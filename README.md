
# Hospital-Dashboard

Snaps of Hospital

![Image](https://github.com/user-attachments/assets/fcb275c8-bedc-4774-ad71-9937c4e6474d)

## Problem Statement
This dashboard helps hospitals understand their patients better. It enables the hospital staff to know if their patients are satisfied with their services. Through different ratings, they get to know their areas for improvement, allowing them to enhance their services. It also helps to track average wait times and other key metrics, thereby helping to identify and work on minimizing delays and other inefficiencies.

Since the number of neutral/dissatisfied patients is high, efforts must be made to improve the quality of care and services.

### Steps Followed
1. **Load Data into Power BI Desktop**: The dataset is a JSON file.
2. **Open Power Query Editor**: Check "column distribution", "column quality," and "column profile" options.
3. **Column Profiling**: Ensure profiling is based on the entire dataset.
4. **Handle Missing Values**: Identify and manage columns with missing or null values.
5. **Calculating Average Metrics**: Null values in columns like "Patient Satisfaction Score" and "Patient Wait Time" are handled appropriately.
6. **Theme Selection**: Apply a suitable theme to the report.
7. **Add Visuals**: Represent ratings and other metrics using appropriate visuals.
   - Use Slicers for fields like "Department Referral", "Patient Gender", and "Patient Race".
   - Use card visuals for average wait times and patient satisfaction scores.
8. **Bar Charts and Legends**: Represent the number of satisfied and neutral/unsatisfied patients, segregated by gender and other demographics.
9. **Ratings Visuals**: Represent different ratings such as:
   - Admission Experience
   - Hospital Cleanliness
   - Staff Friendliness
   - Ease of Appointment Booking
   - In-patient Services
   - Out-patient Services
   - Overall Satisfaction
10. **Text Boxes and Shapes**: Add hospital name, tagline, and logo to the report.
11. **Calculated Columns**: Group patients into various age groups using DAX expressions.
12. **Measures**: Create new measures to find total count of patients, percentage distribution, and other key metrics.
13. **Publish**: Publish the report to Power BI Service.

## Insights
A single-page report was created on Power BI Desktop and then published to Power BI Service. The following inferences can be drawn from the dashboard:

### Total Number of Patients
- **Total Number of Patients**: 10

### Patient Details
#### Patient 1
- **Patient Id**: 316-34-3057
- **Admission Date**: 15-06-2024 11:29
- **Gender**: Male
- **Age**: 4
- **Race**: Native American/Alaska Native
- **Department Referral**: None
- **Admission Flag**: TRUE
- **Satisfaction Score**: (missing)
- **Wait Time**: 27 minutes

#### Patient 2
- **Patient Id**: 897-46-3852
- **Admission Date**: 20-06-2024 09:13
- **Gender**: Female
- **Age**: 56
- **Race**: African American
- **Department Referral**: General Practice
- **Admission Flag**: TRUE
- **Satisfaction Score**: 9
- **Wait Time**: 55 minutes

#### Patient 3
- **Patient Id**: 358-31-9711
- **Admission Date**: 04-02-2024 22:34
- **Gender**: Female
- **Age**: 24
- **Race**: Native American/Alaska Native
- **Department Referral**: General Practice
- **Admission Flag**: TRUE
- **Satisfaction Score**: 8
- **Wait Time**: 31 minutes

#### Patient 4
- **Patient Id**: 289-26-0537
- **Admission Date**: 04-09-2024 17:48
- **Gender**: Male
- **Age**: 5
- **Race**: African American
- **Department Referral**: Orthopedics
- **Admission Flag**: FALSE
- **Satisfaction Score**: (missing)
- **Wait Time**: 10 minutes

#### Patient 5
- **Patient Id**: 255-51-2877
- **Admission Date**: 20-04-2023 00:13
- **Gender**: Male
- **Age**: 58
- **Race**: Asian
- **Department Referral**: None
- **Admission Flag**: FALSE
- **Satisfaction Score**: (missing)
- **Wait Time**: 59 minutes

#### Patient 6
- **Patient Id**: 465-97-0990
- **Admission Date**: 23-08-2023 08:26
- **Gender**: Female
- **Age**: 68
- **Race**: White
- **Department Referral**: None
- **Admission Flag**: TRUE
- **Satisfaction Score**: (missing)
- **Wait Time**: 43 minutes

#### Patient 7
- **Patient Id**: 157-31-7520
- **Admission Date**: 29-07-2023 16:57
- **Gender**: Female
- **Age**: 47
- **Race**: Two or More Races
- **Department Referral**: None
- **Admission Flag**: TRUE
- **Satisfaction Score**: (missing)
- **Wait Time**: 23 minutes

#### Patient 8
- **Patient Id**: 432-34-5614
- **Admission Date**: 19-02-2024 06:54
- **Gender**: Female
- **Age**: 79
- **Race**: White
- **Department Referral**: None
- **Admission Flag**: FALSE
- **Satisfaction Score**: 1
- **Wait Time**: 42 minutes

#### Patient 9
- **Patient Id**: 609-17-8678
- **Admission Date**: 11-10-2024 05:25
- **Gender**: Male
- **Age**: 62
- **Race**: African American
- **Department Referral**: None
- **Admission Flag**: FALSE
- **Satisfaction Score**: (missing)
- **Wait Time**: 51 minutes

### Average Ratings
- **Admission Experience**: (To be determined)/5
- **Hospital Cleanliness**: (To be determined)/5
- **Staff Friendliness**: (To be determined)/5
- **Ease of Appointment Booking**: (To be determined)/5
- **In-patient Services**: (To be determined)/5
- **Out-patient Services**: (To be determined)/5
- **Overall Satisfaction**: (To be determined)/5

### Average Wait Time
- **Average Wait Time in Minutes**: (To be determined)

### Demographic Insights

#### Patient Age Groups
1. **0-25**: (To be determined)%
2. **25-50**: (To be determined)%
3. **50-75**: (To be determined)%
4. **75-100**: (To be determined)%

#### Patient Race
1. **White**: (To be determined)%
2. **African American**: (To be determined)%
3. **Native American/Alaska Native**: (To be determined)%
4. **Asian**: (To be determined)%
5. **Two or More Races**: (To be determined)%

#### Department Referral
1. **General Practice**: (To be determined)%
2. **Orthopedics**: (To be determined)%
3. **None**: (To be determined)%

---
