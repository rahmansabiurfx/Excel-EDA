# Patient Data Analysis Report

## Cleaning
- Loaded the raw CSV data into Excel for analysis.
- Removed personally identifiable information (First Name, Last Name) to maintain patient privacy.
- Checked for null values and corrected inconsistent categorical values.

## Processing
- Split the datetime field into separate **Date** and **Time** columns.
- Created a **Weekend indicator column** to distinguish between weekday and weekend visits.
- Added **Month** and **Year** columns to enable time series analysis.
- Included a dedicated **Month column** to identify seasonal trends in patient visits.

## Analysis and Visualization
### Wait Times
- **General Practice** had the longest average wait time (~37.5 minutes), significantly higher than other departments.
- **Cardiology** and **Gastroenterology** recorded the shortest average wait times (~13.5 minutes).
- **Neurosurgery** and **Orthopaedics** showed moderate wait times (22.5–25.5 minutes).

### Department Visit Volumes
- **General Practice** was overwhelmingly the busiest department, with ~1200 weekday visits and ~800 weekend visits.
- All other departments had significantly lower visit volumes.
- **Cardiology** had the second-highest weekend visit volume, making it an important area for weekend staffing.
- **Renal** and **Physiotherapy** recorded the lowest overall visit numbers.

### Demographics
- The highest number of visits for both genders occurred in the **Adult** and **Middle Aged** groups.
- Female patients had higher visit counts across all age groups compared to males, with the largest differences in the **Adult** and **Middle Aged** categories.
- Male visits were notably low in the **Child** and **Teen** groups.

## Conclusion
- The high patient load in **General Practice** explains its elevated average wait times, making it a clear bottleneck. This department should be the primary focus for efficiency improvements.
- Staffing should be prioritized for **General Practice**, particularly on weekdays.
- Additional weekend staffing in **Cardiology** should be considered, as it is the second busiest department on weekends.