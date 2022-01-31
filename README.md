# School_District_Analysis

<!-- Overview of the school district analysis: Explain the purpose of this analysis. -->
## Overview
The purpose of this project is to examine csv files regarding 15 schools and their students' math and reading scores then compare the effects of excluding Thomas High School(THS)'s ninth grade scores.

## Resources
Data source: schools_complete.csv, students_complete.csv
Software: Python 3.7, Anaconda 4.11.0, Jupyter Lab, Pandas, Numpy

<!-- Results: Using bulleted lists and images of DataFrames as support, address the following questions.
How is the district summary affected?
How is the school summary affected?
How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
How does replacing the ninth-grade scores affect the following:
Math and reading scores by grade
Scores by school spending
Scores by school size
Scores by school type -->
## Results
- District summary
  - The original average math score was approximately 79.0. The new score excluding THS ninth graders was approximately 78.9. Difference between the two was 0.1. Since the digits of precision between the two summaries are displayed differently, the values from the last three columns would round to be the same should they be formatted to have no digits after the decimal. 
  - If the scores and percentages displayed contained more digits of precision, the trailing digits would likely be different between the two sets of values. However, the digits of precision was most accurately displayed with the original district summary. Any additional trailing digits that are displayed, as with the other DataFrames below, hold little significance.

District summary is shown below.

![district_summary_0](https://user-images.githubusercontent.com/96349090/151691799-ffdd32cb-c51c-47bb-ab43-d1d66957d63e.png)

District summary excluding THS ninth grade scores is shown below.

![district_summary_1](https://user-images.githubusercontent.com/96349090/151691748-b8ed9b51-43d2-4a2f-80d3-4471b9dda164.png)

- School summary
  - The average reading score of THS changed from 83.8 to 83.9.
  - The percentage of students that passed math from THS changed from 93.3% to 93.2%.
  - The percentage of students that passed reading from THS changed from 97.3% to 97.0%.
  - The percentage of students that passed both math and reading from THS changed from 90.9% to 90.6%.

School summary is shown below.

![school_summary_0](https://user-images.githubusercontent.com/96349090/151691806-56ee543d-19d0-4b16-83e7-d0ef1e8ff6ff.png)

School summary excluding THS ninth grade scores is shown below.

![school_summary_1](https://user-images.githubusercontent.com/96349090/151691761-1e01a4fa-8295-470a-a8e9-3d686eda0614.png)

- Top and bottom performing schools
  - Excluding the ninth graders’ math and reading scores did not affect THS’s performance relative to the other schools.

Top and bottom five performing schools is shown below.

![top5_bottom5_0](https://user-images.githubusercontent.com/96349090/151691819-445850a3-7007-481f-b5f9-be7db3ba9345.png)

Top and bottom five performing schools, excluding THS ninth grade scores, is shown below.

![top5_bottom5_1](https://user-images.githubusercontent.com/96349090/151691769-26582936-d8dc-4ec1-a365-75f665a39e05.png)

- Average math and reading scores by grade per school
  - Excluding the ninth graders’ math and reading scores did not affect any scores other than ninth grade.

Average math scores by grade per school is shown below.

![math_0](https://user-images.githubusercontent.com/96349090/151691826-714d7d2f-a30e-4731-bca5-682ac7f65eff.png)

Average math scores by grade per school, excluding THS ninth grade scores, is shown below.

![math_1](https://user-images.githubusercontent.com/96349090/151691784-9debd5ac-3e59-4413-b7da-cdc024a82071.png)

Average reading scores by grade per school is shown below.

![read_0](https://user-images.githubusercontent.com/96349090/151691836-1ebb2499-058b-460b-a416-157ee455167c.png)

Average reading scores by grade per school, excluding THS ninth grade scores, is shown below.

![read_1](https://user-images.githubusercontent.com/96349090/151691790-8494ebbc-9574-439e-8578-4303dbe22545.png)

- Scores by school spending, school size, and school type
  - Excluding the ninth graders’ reading scores did not affect any scores when categorizing by school spending, school size, or school type.

Scores by school spending for both including and excluding THS ninth grade scores is shown below.

![school_spending_1](https://user-images.githubusercontent.com/96349090/151691705-e6984678-55a2-4f2f-8b1c-d236e67eb913.png)

Scores by school size for both including and excluding THS ninth grade scores is shown below.

![school_size_1](https://user-images.githubusercontent.com/96349090/151691700-0391c3d0-a4bb-4c71-9e49-835ea675252c.png)

Scores by school type for both including and excluding THS ninth grade scores is shown below.

![school_type_1](https://user-images.githubusercontent.com/96349090/151691695-5139d8be-3876-443a-bba0-ada06de99f1d.png)


<!-- Summary: Summarize four changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs. -->
## Summary
Four changes in the updated school district analysis after excluding reading and math scores for the ninth grade at THS include:
1. The average reading score of THS changed from 83.8 to 83.9, which suggests that tenth through twelve grade reading scores are slightly higher that of ninth grade scores.
2. The percentage of students that passed math from THS changed from 93.3% to 93.2%, which suggests that slightly more ninth graders passed math than other grades.
3. The percentage of students that passed reading from THS changed from 97.3% to 97.0%, which suggests that slightly more ninth graders passed reading than other grades.
4. The percentage of students that passed both math and reading from THS changed from 90.9% to 90.6%, which suggests that slightly more ninth graders passed math and reading than other grades.
