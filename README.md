# School_District_Analysis
## OBJECTIVE ## 
Chief Data Scientist Maria works for a City School District. She is responsible for analyzing information from various sources. Maria inquired me to assist her with analyzing standardized testing data to report on trends. Upon review, the school board notified Maria and her supervisor that the students_complete.csv file showed evidence of academic dishonesty- specifically Thomas High School's ninth grade reading and math scores. In order to uphold state testing standards, the school board turned to Maria for help. Maria asked me to replace the math and reading scores for Thomas High School with NaNs while keeping the rest of the data intact; she also requested that I replace the math and reading scores, repeat the school district analysis from the module and describe how the changes effected the overall analysis.

_______________________________________________________________________________________________
## RESULTS ##
1. How is the District Summary Affected?

We applied 'NaN' to declare Thomas High School 9th grade as numerically invalid


![NaN](https://user-images.githubusercontent.com/77905862/128958307-1c639ce2-1357-4e9a-b704-c3c2250c3905.png)



- The overall passing percentage decreases from the original score of 65 to 64.9
- The average reading score increased by 0.01
- The passing math percentage decreased by 0.01
- The passing reading percentage and average math score remained relatively the same as the original data frame.

**There were no significant changes**

[**PRIMARY DISTRICT SUMMARY**]

![District Summ Changes Primary](https://user-images.githubusercontent.com/77905862/128957976-3933fc78-982c-4352-a257-0396ef1dbe48.png)
[**SECONDARY DISTRICT SUMMARY**]

![District Summ Changes](https://user-images.githubusercontent.com/77905862/128958058-d66341aa-3d96-4cfd-82ae-08e433744475.png)


2. How is the School Summary Affected?

[**PRIMARY SCHOOL SUMMARY**]

![School Summary Primary](https://user-images.githubusercontent.com/77905862/128960119-59e22399-eb82-4541-b696-8ee303772e4f.png)
[**SECONDARY SCHOOL SUMMARY**]

![Proper Code](https://user-images.githubusercontent.com/77905862/128960521-4cf4a16c-ca73-4540-82d7-6a0bf2f4f8ac.png)


The school summary [Thomas High School 10th-12th considered ONLY] is affected as follows:
- Passing math score decreased from the original percentage of 93.2 to 93.18
- Passing reading scores decreased from the original percentage of 97.30 to 97.01
- Overall passing scores decreased from the original percentage of 90.94 to 90.63

Scores by school type

## SUMMARY ##

In summary, upon removing and/or replacing Thomas High School ninth grade data, Maria and I came to the conclusion that no significant changes took place- indicating that the primary data analysis was relatively accurate. 
It is safe to say that Thomas High School ninth grade has maintained it's academic integrity.
