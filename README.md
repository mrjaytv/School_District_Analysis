# School_District_Analysis

## Overview and Purpose of Project 
Maria, the Chief Data Scientist, for a city school district is responsible for analyzing information from a variety of sources, and in a variety of formats. She prepared all standardized test data for analysis, reporting, and presentation to provide insights about performance trends and patterns. These insights are used to inform discussions and strategic decisions at the school and district level. Our team was tasked to aggregate the data and show case trends in school performance with access to the students_complete.csv and schools_complete.csv. The analysis completed in [PyCitySchools.ipynb](https://github.com/mrjaytv/School_District_Analysis/blob/2de66af30289f809ae51e5497f59a177d7ff1df2/PyCitySchools.ipynb) helped Maria analyze data on student funding and students’ standardized test scores. 

After our analysis, the school board notified Maria and her supervisor that the `students_complete.csv` file showed evidence of academic dishonesty; specifically, reading and math grades for Thomas High School ninth graders appear to have been altered. Although the school board does not know the full extent of the academic dishonesty, they want to uphold state-testing standards and have turned to Maria for additional help. Maria, once again reached out with additional requirements

### Data Requirements: 
- Replace the math and reading scores for Thomas High School with NaNs while keeping the rest of the data intact.
- Repeat the school district analysis and describe how these changes affected the overall analysis.

## Results
Using the Pandas `loc` method with conditional statements and comparison and logical operators, selecting the ninth-grade reading and math scores for Thomas High School. Then, we will use the Pandas NumPy module to change the reading and math scores to NaN. This caused some minor to no changes to the results for district and school analysis. 


### District Summary
As shown in the image below, when removing the 9th grade Math and Reading scores from our data this causes the scores to slightly decrease. 


### School Summary
As shown in the image below, when removing the 9th grade Math and Reading scores from our data this then reflects a positive increase for the subject percentages and overall passing percentage.   

How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools? 

### High and Low Performing Schools
How does replacing the ninth-grade scores affect? 


### Math and Reading Scores by Grade
How does replacing the ninth-grade scores affect? 


### Scores by School Spending
How does replacing the ninth-grade scores affect? 


### Scores by School Size
How does replacing the ninth-grade scores affect? 


### Scores by School Type
How does replacing the ninth-grade scores affect? 


## Summary



