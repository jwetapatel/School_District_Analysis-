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


- As per above anylysis we can conclude that average math and reading scores of Thomas High School bacame 0 from 83.6 and 83.7 respectively. 
- Compare to other schools Thomas high aschool perfomance is very low.

## Replacing the ninth-grade scores affect the following:

### Math and reading scores by grade
- Here are our Top 5 Schools as per math and reading scores and avereage percentage 

![Screenshot 2022-05-top5 school](https://user-images.githubusercontent.com/96400887/168186364-fdbf62f5-ea06-44df-8adb-e326228f6458.png)

- Here are our Bottom 5 Schools as per math and reading scores and avereage percentage 

![Screenshot 2022-05-bottom 5](https://user-images.githubusercontent.com/96400887/168186531-d43d33a8-9d7a-43e3-8ea1-5c2f91e2fdef.png)

### Scores by school spending summary

![Screenshot 2022-05-12 spending per school](https://user-images.githubusercontent.com/96400887/168187500-2a5f187d-57eb-4be5-8fec-8b971c44d1c0.png)

![Screenshot 2022-05-spending_data](https://user-images.githubusercontent.com/96400887/168187514-6a26d285-8848-47e5-b9e4-c434631ac437.png)

- Based on above output we anylyzed that School that spent between <$584 appear to have the best-performing students in math and reading. So the schools which spent the lowest are the highest performing shcool in Math & Reading.

### Scores by school size

![Screenshot 2022-05-12 school size data](https://user-images.githubusercontent.com/96400887/168188000-2e513d99-9cc5-4a59-8bfb-fcbb1f57f8aa.png)

- Scores by school size were calculated by determining size ranges for all 15 schools in the district:

- Small (<1000) -Medium (1000-2000) -Large (2000-5000)

- When considering School Sizes, "Large" Schools (Over 2,000 Students) have the lowest average scores and passing percentages. The difference in performance between "Small" and "Medium" Size Schools is negligible (approximately 1%). Interestingly, all District schools in this dataset are characterized as "Large" schools. This may be an indication that students in this district learn and perform better in smaller, more intimate settings.

### Scores by school type (Charter vs District Schools)

![Screenshot 2022-05-12 school type output](https://user-images.githubusercontent.com/96400887/168188123-e92749c6-e5f7-4918-9a10-42680d6574a3.png)

- Charter schools performed better than District schools in this analysis. The top five schools with the highest overall passing percentages are all Charter schools, whereas the bottom five are all District Schools. Charter schools in this dataset were typically characterized as "Small" and "Medium" size schools. As seen in the DataFrame below, Charter schools have a 36% higher overall passing percentage than District schools.

# Summary :

- Relacing the ninth graders' scores with NaN caused Thomas High School's overall passing percentages and average scores got dropped. The district also had its average math and reading scores decrease, as well as the overall passing percentage for students. Furthermore, Thomas High School lost its placement as a top five school within this District.
- However, after updating the total student counts to exclude the Thomas High School ninth graders and omitting their scores from the dataset, Thomas High School regained its high average scores and retained its position as the number two school in the District.
















