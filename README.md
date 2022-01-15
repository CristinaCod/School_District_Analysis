# School District Analysis
## Overview
### Purpose
The purpose of this school district analysis is to assist Maria, the chief Data Scientist for a city school system, in analyzing data on school funding and test scores. By analyzing all student standardized test reading and math scores in conjunction with various information on the schools they attend we can then compile this data to provide insight on performance trends. These findings can then be used to assist the school board in making important decisions on school budgets and lesson priorities. These findings can also be applied at both a school and district level. After our initial analysis evidence of academic dishonesty was discovered amongst the ninth graders at Thomas High School so those grades had to be augmented and the analysis re-run. Below is the presentation of those findings. 

## Results
* How the district summary is affected:

With the new analysis the values in the district summary are just about 1% less for each category. "% Passing Math" changed from 75% originally to now 73.9%. "% Passing Reading" changed from 86% originally to 84.7%. Lastly, we saw the "% Overall Passing" go from 65% originally to 64.1%. Visualizations provided below.

![original_district_summary.png](https://github.com/CristinaCod/School_District_Analysis/blob/main/Resources/original_district_summary.png)

![new_district_summary.png](https://github.com/CristinaCod/School_District_Analysis/blob/main/Resources/new_district_summary.png)

* How the school summary is affected:
  
 In the overall school summary the average math and reading scores showed no changes with the new data. However, we did see changes to the passing percentages of math and reading. "% Passing Math" changed to 93.2%. "% Passing Reading" went from 69.7% to 97%. And "% Overall Passing" went from 65% to 90.6%. Current summary provided below with Thomas High School highlighted as the last row.
 
 ![per_school_summary_df.png](https://github.com/CristinaCod/School_District_Analysis/blob/main/Resources/per_school_summary_df.png)
 
* How replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools:

 After replacing the ninth graders' at Thomas High School's math and reading scores we found that ...
 
* How replacing the ninth-grade scores affects the following:

  -Math and reading **scores by grade:**
  
  There appeared to be no change in math and reading scores by grade when comparing the new test scores of ninth graders at Thomas High School with the original findings. Only difference we see when looking at the scores by grade series is that the ninth graders at Thomas High School have "nan" instead of a numerical value.
  
  -Scores by **school spending:**
  
  After incorporating the new standardized test scores from the ninth graders at Thomas High School we did not see any significant differences in the spending ranges per student compared to the original findings before retesting. 
  
  -Scores by **school size:**
  
  After comparing the analysis with the new test scores from the ninth graders at Thomas High School it is clear that there was no signficant effect and those findings reflect the original ones exactly.
  
  -Scores by **school type:**
  
We found that after running the analysis with the new grades from the ninth graders at Thomas High School there was no significant impact and the findings are still equivalent to those of the original analysis before reports of dishonesty arose.


## Summary
After running the new school district analysis and removing the dishonest ninth graders math and reading scores from Thomas High School, the rest of the grades at the high school did see a significant increase in their passing percentages proving that the ninth graders were hindering the academic success of their peers. This then also reflects poorly on the school itself and district as a whole which could then effect the fundings and resources they receive. As mentioned we did also see the negative effects the ninth graders dishonesty had on the district summary as a whole. Whether or not the one percent difference is significant or not can be debated but if considered signififcant this could effect school and district rankings bringing them down which could also manifest into not receiving as much funding and perhaps a lack of desire for parents to send their children there when looking for schools. 
