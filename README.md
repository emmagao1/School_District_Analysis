# School_District_Analysis

## Overview of the school district analysis: Explain the purpose of this analysis.

Helping school board to analyze academic scores by replacing Thomas High School 9th grader's match and reading scores to NaNs to determine the impact of score changes to the overall district summary analysis and school summary analysis.

## Results: Using bulleted lists and images of DataFrames as support, address the following questions.

* **How is the district summary affected?**

District summary including Thomas High School 9th graders
![District summary including Thomas High School 9th graders](https://github.com/emmagao1/School_District_Analysis/blob/master/district%20summary%20including%20thomas%20high.PNG)

District summary excluding Thomas High School 9th graders
![District summary excluding Thomas High School 9th graders](https://github.com/emmagao1/School_District_Analysis/blob/master/district%20summary%20excluding%20thomas%20high.PNG)

Overall district summary is not affected and passing rate fluctuate less than 1% shown in the table above. Pssing math percentage dropped 0.2% and passing reading percentage dropped 0.1% after replacing Thomas High School 9th grader's math and readign score to NaN and overall passing percentage dropped 0.3%.

* **How is the school summary affected?**

School Summary including Thomas high 9th graders
![School Summary including Thomas high 9th graders](https://github.com/emmagao1/School_District_Analysis/blob/master/School%20Summary%20including%20Thomas%20high%209th%20graders.PNG)

School Summary excluding Thomas high 9th graders
![School Summary excluding Thomas high 9th graders](https://github.com/emmagao1/School_District_Analysis/blob/master/School%20Summary%20excluding%20Thomas%20high%209th%20graders.PNG)

Other than Thomas High School, all other schools results remain unchanged. Thomas High School passing math percentage dropped 26.36%., passing reading percentage dropped 27.65% and overall passing percentage dropped 25.87%. 

* **How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?**

Overall performance before replacing Thomas High School 9th graders math and reading scores
![overall passing including thomas high](https://github.com/emmagao1/School_District_Analysis/blob/master/overall%20passing%20including%20thomas%20high%20after%20score%20replacement.PNG)

Overall performance after replacing Thomas High School 9th graders math and reading scores
![overall passing excluding thomas high](https://github.com/emmagao1/School_District_Analysis/blob/master/overall%20passing%20excluding%20thomas%20high.PNG)

Before replacing 9th grader scores to NaN, Thomas High School was included in top 5 performing schools and after replacing scores, it dropped out of top performance schools. 

* **How does replacing the ninth-grade scores affect the following:**

  - **Math and reading scores by grade after replacing the ninth-grade scores**

![math score by grade after score replacement](https://github.com/emmagao1/School_District_Analysis/blob/master/Math%20score%20by%20grade%20after%20thomas%20score%20replacement.PNG)

![reading score by grade after score replacement](https://github.com/emmagao1/School_District_Analysis/blob/master/Reading%20score%20by%20grade%20after%20thomas%20score%20replacement.PNG)
 
There is no significant change other than 9th graders score got replaced.

 - **Scores by school spending**
 
Before replacing the ninth-grade scores
 
![Scores by school spending after score replacement](https://github.com/emmagao1/School_District_Analysis/blob/master/school%20spending%20scores%20after%20thomas%20high%20replacement.PNG) 

After replacing the ninth-grade scores
![Scores by school spending BEFORE score replacement](https://github.com/emmagao1/School_District_Analysis/blob/master/school%20spending%20scores%20BEFORE%20thomas%20high%20replacement.PNG)

Spending range $630-644 was impacted by replacing Thomas High ninth-grade scores shown in the tables above:

  1. % Passing Math dropped by 6%
  2. % Passing Reading dropped by 7%
  3. % Overall Passing dropped by 7%

 - **Scores by school size** 

Before replacing the ninth-grade scores

![Scores by school size after score replacement](https://github.com/emmagao1/School_District_Analysis/blob/master/school%20size%20scores%20after%20thomas%20high%20replacement.PNG)

After replacing the ninth-grade scores
 
![Scores by school size BEFORE score replacement](https://github.com/emmagao1/School_District_Analysis/blob/master/school%20size%20scores%20BEFORE%20thomas%20high%20replacement.PNG)
 
School size medium (1000-2000) was impacted by replacing Thomas High ninth-grade scores shown in the tables above:

 1. % Passing Math dropped by 6%
 2. % Passing Reading dropped by 6%
 3. % Overall Passing dropped by 6%
 
  - **Scores by school type** 

Before replacing the ninth-grade scores

![Scores by school type after score replacement](https://github.com/emmagao1/School_District_Analysis/blob/master/school%20type%20scores%20after%20thomas%20high%20replacement.PNG)

After replacing the ninth-grade scores
  
![Scores by school type BEFORE score replacement](https://github.com/emmagao1/School_District_Analysis/blob/master/school%20type%20scores%20BEFORE%20thomas%20high%20replacement.PNG)

Charter school was impacted by replacing Thomas High ninth-grade scores shown in the tables above:

  1. % Passing Math dropped by 4%
  2. % Passing Reading dropped by 4%
  3. % Overall Passing dropped by 3%

## Summary: Summarize some major changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.

  - Thomas High School % Passing Math dropped 26.36% after replacing nith grade with NaNs 
  - Thomas High School % Passing Reading dropped 27.65% after replacing nith grade with NaNs 
  - Thomas High School % Overall Passing dropped 25.87% after replacing nith grade with NaNs 
  - **Note the percentage drop is after replacing 9th grades with NaNs and before replacing NaNs to 10th-12th grade's passing percentage.**
