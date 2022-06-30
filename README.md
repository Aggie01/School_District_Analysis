# School_District_Analysis
## Background:
- Standardized math and reading scores for **9th, 10th, 11th and 12th graders** for the city school district were gathered.  
- Data scientist for the school district was asked to present the findings to the city school board. 
- Based on preliminary analysis, evidence of the academic dishonesty was suspected, suggesting that the THS scores were significantly skewed.

## Purpose:
- **Prove** the evidence of academic dishonesty with the main focuse on Thomas High School (THS) or
- **Disprove** the evidence of such academic dishonesty 

## Main Goal:
- Establish conclusion wheather the evidence of suspected THS school dishonesty was properly collected

## Methodology:
- Refactoring the THS student count by replacing the 9th graders' math and reading scores with NaN's while keeping the rest of data intact

## Expected Deliverables: 
- Overall district summary
- School summary (THS)
- Impact or lack of it of replacing THS 9th graders' math and reading scores with NaNs:
  - overall THS performance vs other schools
  - math & reading scores by grade
  - school spending
  - scores by school size
  - scores by school type
        
## Results:
### Overall district summary
- Averages score for math: 78.9%
- Average score for reading: 81.8%

### Thomas High School summary including 9th, 10th, 11th and 12th graders
- Averages score for math: 83.4%
- Average score for reading: 83.8%
- Passing math percentage: 66.9%
- Passing reading percentage: 69.6%
- Overall passing math and reading: 65%

### Impact of replacing THS ninth graders' math and reading scores with NaNs
- Passing math percentage: 93.2%
- Passing reading percentage: 97%
- Overall passing math and reading: 90%
- school spending was not affected

### Summary
The passing percentages for math, reading and overall have increased significantly after dropping the THS 9th graders. It proves the point that there was a significant number of high scoring students as compared to other schools. Other schools had close to  normal distribution of passing grades around the average of math and reading scores.  Removing THS 9th graders, made the THS results more aligned with other schools' results - similar distribution of passing grades.  The 9th graders skewed the school's passing results. This data analysis could be a basis for repeating THS 9th grade standardized math and reading testing.
School spending was not affecting by this change.





