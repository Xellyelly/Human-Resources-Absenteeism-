# Human-Resources-Absenteeism-

### project overview
This report examines the factors contributing to absenteeism in the workplace and determine how to help those who are missing work.  It focuses on key features such as age, season, lifestyle factors, and work-related variables to identify patterns and provide actionable insights.

### Data source 
The primary data sets used for this analysis are "Absenteeisms.csv" and "Employee_info" 

### Tools
power bi (DAX)
power bi (Visualisation)


### Data Preparation Process
Feature Engineering:
- Group age into 27-30,31-40,41-50,53-58
- Calculate BMI using individual employee weight and height
- Grouping month of the year into seasonal (spring, autumn, winter, summer)

#### Encoding Categorical Variables:
- Converting one hot coding into categorical coding
### Key Findings
- Total absences are 639
- Total number of employees is 37
-	Number of employees with more than 2 children and at least one pet is 8
-	Only two employees are absent once

### Data Analysis and Insights
4.2. Absenteeism Trends by Season
-	The season with the highest count of absentee reported is spring, total absences of 195 and majority of the employees which are 30 in numbers are absence during this period
-	The season with the lowest count of absentee reported is winter, total absences of 138 and 24 employees are absence during this period
-	The month with the highest count of absentees is match, which might be as result of work load average, because highest workload average is also recorded in match
-	Other category name as others which consist only three employee, with just three number of absentees
4.2. Absenteeism Trends by average work load
-	There is a positive correlation between average work load and absenteeism, as the average workload increases, the number of absentees also increases.  Higher workloads may lead to stress, burnout, or fatigue, increasing absenteeism.  Employees may take more sick days due to physical or mental exhaustion. Overworked employees may feel demotivated and take more unplanned leaves
  ![Screenshot 2025-03-16 095840](https://github.com/user-attachments/assets/118947d8-8ef8-4ada-a5d2-7f64635bcd5c)
-	Workload is not evenly distributed across all age groups, age of 28-47 experience greater work, almost throughout the month compare to other a
age group
![Screenshot 2025-03-15 165656](https://github.com/user-attachments/assets/d0d86565-f1cc-43c7-93ad-c47e25c40218)
4.2. Absenteeism Trends by Body Mass Index (BMI) categories
-	BMI IS Calculated by dividing the weight of and employee by the corresponding height multiply 100 with square of 2
  ![Screenshot 2025-03-15 152711](https://github.com/user-attachments/assets/805b09a0-9098-4fa3-94c5-222762e07105)
- BMI is grouped into 3 categories of underweight, Normal weight, overweight and obese, none of the employees fall under the underweight category
  ![Screenshot 2025-03-15 152736](https://github.com/user-attachments/assets/7efc5d25-0e25-4919-b7fc-37c5b042eec9)
-	The total number of employees with normal weight is 21, and total number of absenteeism is 318. Education level: 16.35% are post graduate, graduate are about 8.81% and 74.84% are high school, 5 are smokers and 10 are drinkers

-	The total number of employees with over weight is 7, and total number of absenteeism is 92. Education level: masters and doctors 5.43%, 20.65% of post graduate, 58.70% is high school, graduate is about 15.22% ,1 smoker and 3 are drinkers

-	The total number of employees with obesity is 9, and total number of absenteeism is 229. Education level;100% are high school, 1 smoker and 6 are drinkers, 62.88% falls within the age group of 31-40 and 37.12%they are 41 to 50 years of age 

-	Others are distributed across the age bin
  ![Screenshot 2025-03-15 160949](https://github.com/user-attachments/assets/6751b263-fa56-487b-b0b0-70568e67803e)

### 4.3. Absenteeism Trends by reasons of absent
-	88.31% of reason why employees are absent is due to medical reasons, the highest absentees recorded based on this reason occur in march which may due to ethic work, absenteeism recorded is 555 by 33 employers 
-	5.54% of reason why employees are absent is due incomplete submission, 3 employees on the other group of the month have incomplete submission as reason for absent
-	4.69% of reason why employees are absent are due to unjustified leave
-	3.13% of reason why employees are absent due to family related issue 
-	Absenteeism by all this reason is evenly distributed across age bin, age has no relationship on reasons of absenteeism
  ![Screenshot 2025-03-15 165257](https://github.com/user-attachments/assets/40e2ff16-55c8-4a77-8570-c84ba223d9fe)
### 4.4. Absenteeism based on distance of home to work
-	The distance of home to work greatly affect number of absenteeism the whole distance ranges from 5 to 52
-	Employees with the distance of 5 to25 to work are 18, and total absenteeism is 208, 3 of these employees has more than two children and at least one pet from 8 recorded
-	Employees with the distance of 26 to 52 to work are 19, and total absenteeism is 431 more than times two of employees living closer to work, 5 of these employees has more than two children and at least one pet from 8 recorded of the entire employees
-	There two employees that are absent once, with id of 4 and 35 and the distance from home is 14 and 10 respectively
  ![Screenshot 2025-03-15 165656](https://github.com/user-attachments/assets/ba1a2c9b-6837-48b8-b653-684a548aa193)






  

  



 
  
  





 




















