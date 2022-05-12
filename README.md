# School_District_Analysis
Using Python, Pandas and Jupyter notebook

# Overview of the school district analysis :

The purpose of the project is to heip Maria to analyze the following data of the High Schools before and after a possible academic dishonesty, where the data for 9th Grade of Thomas High School has been upheld for the analysis purpose. We have replaced the math and reading scores for Thomas High School with NaNs while keeping the rest of the data intact. We will analyse the data before and after making this change.

- The School and district summary.

- The top 5 and bottom 5 performing schools, based on the overall passing rate.

- The average math and Reading scores for each grade level from each school.

- School performance based on the budget per student

- The scores by school spending per student, by school size, and by school type.

# Resources :

- Data Source: schools_complete.csv, students_complete.csv

- Software: Python, Anaconda, Jupyter Notebook, Pandas

# Results :

- The school board has notified Maria and her supervisor that the students_complete.csv file shows evidence of academic dishonesty; specifically, reading and math grades for Thomas High School ninth graders appear to have been altered. Although the school board does not know the full extent of the academic dishonesty, they want to uphold state-testing standards and have asked us to work on specifically Thomas High School 9th grade numbers.

- In order to scrutinize the Thomas High School 9th graders it was best to only replace their math and reading scores while keeping all other data associated with this student group intact.

- Both math and reading scores were replaced with "NaN", which represents a "Not-a-Number" value, for 461 student records. Although this may seem like a significant number, these score replacements did not alter data summaries tremendously overall
- And output shows as below

![Screenshot 2022-05-12 083742](https://user-images.githubusercontent.com/96400887/168114613-720c7cac-58d3-4876-b31a-48e9f72a03fa.png)

## District Summary :

![Screenshot 2022-05-12 134947](https://user-images.githubusercontent.com/96400887/168165761-733749d9-5351-43dd-bda0-3f243a816185.png)

- The data remains unaffected in terms of Total Schools, Total Students and Total Budget as per above analysis.
- Another plus side from this data replacement is that it did not change the math and reading scores by grade. Granted, both the average math and reading score summaries were stratisfied by school and grade level. As shown below, the summary tables for Math & Reading Score Grade-wise display "NaN" for ninth grade at Thomas High School whereas the remaining data remained intact.


## School Summary :

- While calculating Per School Budget & per student budget output looks like this and confirm that the metrics for Thomas High School look like this image:

![Screenshot 2022-05-12 133229](https://user-images.githubusercontent.com/96400887/168164377-e49d5aa6-46b9-434e-83d8-3a84209b3614.png)
![Screenshot 2022-05-12 084447](https://user-images.githubusercontent.com/96400887/168117503-cd40768c-57c3-4c44-92c1-41e192f88053.png)

- Average Math Score and Average Reading scores for Thomas High School changed drastically from 83.42 to 59.85 and 83.85 to 60.24 respectively after the change of Data.


## Replacing the ninth graders’ math and reading scores affected Thomas High School’s performance drastically when compared to other schools.

Ninth Grader Maths scores

![Screenshot 2022-05-12 140105](https://user-images.githubusercontent.com/96400887/168167479-61743dac-b4e8-4356-b901-e5ee4fd6b1e7.png)

Ninth Grader Reading scores

![Screenshot 2022-05-12 140134](https://user-images.githubusercontent.com/96400887/168167494-037fe760-fc1e-499b-9ac8-4ec9c879bcda.png)







