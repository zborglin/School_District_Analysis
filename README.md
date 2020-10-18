# School_District_Analysis
Python Application
Comprehensive Statistical Analysis of a DataFrame

## Project Overview
The dataset associated with 15 local schools became corrupted when administration officials detected fraudulent behavior from a subset of the DataFrame associated with Thomas High School (THS). 

The contents related to the request: 
-An audit of school information and test scores
-Analysis of the audited school data and communication of any impacts associated with the DataFrame breach:

1. How is the test score by district summary affected? 
2. How is the test score by school summary affected?
3. How does removal of the compromised data affect Thomas High School's performance relative to the other schools?
4. How does removal of the compromised data affect Thomas High School's: math and reading scores by grade, scores by school spending per student, scores by school size, scores by school type.

## Resources
- Data Sources: students_complete.csv, schools_complete.csv
- Software: Python 3.7

## Summary of Audited School Information
Compromised test scores:
- Thomas High School, 9th Grade Reading and Math scores
### Audited results with compromised results removed:
- Math and Reading Performance by School Type (District or Charter School)
#
![Math and Reading Performance by School Type](https://github.com/zborglin/School_District_Analysis/blob/main/Resources/district_cleanfix.png)
#
  Removal of the 9th grade THS math and reading scores has no significant impact on the district level analysis shown above. The impact is within the precision required for this report. The unrounded summary below shows this minimal impact:
  #
  ![Unrounded Math and Reading Performance by District, Corrupt THS Scores Removed](https://github.com/zborglin/School_District_Analysis/blob/main/Resources/district_cleanfix_unformatted.png)
  #
  With corrupt THS 9th Grade Data:
  #
  ![Unrounded Math and Reading Performance by District, Includes Corrupt THS Scores](https://github.com/zborglin/School_District_Analysis/blob/main/Resources/district_THS_unformatted.png)
  #
- Math and Reading Performance by School
#
![Math and Reading Performance by School](https://github.com/zborglin/School_District_Analysis/blob/main/Resources/school_summary_cleanfix_unformatted.png)
#
  A small impact to the test performance summary of Thomas High School occured due to the compromised 9th grade scores. Removal of all 9th grade scores led to a a 0.1% decrease in the average reading and math scores:
  #
![Highlight Impact of Score Removal](https://github.com/zborglin/School_District_Analysis/blob/main/Resources/school_THS_highlight.png)
#
- How is THS relative performance effected?
  Removal of the 9th grade scores improved THS overall passing % and moved the score from 4th in overall rankings to 2nd.
  #
  ![Top 5 Schools Before Data Removal](https://github.com/zborglin/School_District_Analysis/blob/main/Resources/Top5_bad.png)
  ![Top 5 Schools After Data Removal](https://github.com/zborglin/School_District_Analysis/blob/main/Resources/Top5_cleanfix.png)
  #
- Impact of data removal on THS metrics:
  - Math and reading score by grade:
  #
  ![Math and reading score by grade](https://github.com/zborglin/School_District_Analysis/blob/main/Resources/grade_cleanfix.png)
  #
  Removal of the ninth grade scores can be seen in the socre summary by grade table above
  - Math and reading score by spending:
  #
  ![Math and reading score by spending](https://github.com/zborglin/School_District_Analysis/blob/main/Resources/spending_cleanfix.png)
  #
  Removal of the corrupted data did not significantly impact the school analysis by spending
  - Math and reading score by school size:
  TODO: "Add size_cleanfix"
  #
  ![Math and reading score by school size](https://github.com/zborglin/School_District_Analysis/blob/main/Resources/size_cleanfix.png)
  #
  Removal of the corrupted data did not significantly impact the school analysis by size
  - Math and reading score by school type:
  Removal of the corrupted data did not significantly impact the school analysis by school type
## Summary
While it is unfortunate that suspected academic dishonesty occurred within the 9th grade math and reading scores at Thomas High School, the impact on the summarized results is minimal:
1. Analysis of scores by spending, school size, and school type are not impacted at a level that changes the reported values (i.e. changes are within the required level of precision)
2. The THS average math and reading results changed by 0.1%

However, a deeper dive into the data reveals that this minor changes have a big impact in two areas:
3. There are now no reported 9th grade math and reading scores at THS and it will be important to isolate the incorrect grades so that the whole class isn't adversely effected by this event.
4. The small changes to THS math and reading scores changes the school's relative ranking from 4th to 2nd place for all schools. While the score change is minimal this change in standing is significant. It is reccommended that the incorrect scores in the 9th grade class of THS be isolated so that the majority of that dataset can be reincluded in order to have a more accurate representation of the relative school rankings.