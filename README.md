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
The passing math, reading and overall percentages have increased significantly after dropping the THS 9th graders. It proves that there was a higher number of high scoring students as compared to other schools. Other schools had more normal distribution of passing grades around the average math and reading scores.  Removing THS 9 th graders scores, made the THS results more aligned with other schools- similar distribution of passing grades.
School spending was not affecting by this change.
The 9th graders skewed the results of passing the passing results having the abnormal amout of students with high passign scores



