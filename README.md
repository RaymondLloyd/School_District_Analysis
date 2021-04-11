# School_District_Analysis
## Overview of Analysis
We will be helping Maria perform analysis on a school district to uncover trends and patterns. The results should give insight for the schoolboard officials to make informed decisions regarding school budgets and needs. 

## Resources
-We used Python and Pandas on Jupyter Notebook to execute our analysis.
-Python 3.7.6
-Jupyter Notebook
  
## Challenge Task

We received information about the students test scores In the 9th grade at Thomas High School may have been corrupted. We have been tasked to nullify those scores and replace the data with NaN(Not a Number). We will have to sort through the data and make subsequent changes that will change our Dataset as a whole. 
## Results                                                            
* District Summary
*      
Looking at the previous data we can see that as a district, the scores didn’t change all that much. There was just slight changes in passing percentages.
![district summary old](https://user-images.githubusercontent.com/79877349/114323500-5c7a5080-9ada-11eb-8f0c-f020edad99be.png)
![district summary new](https://user-images.githubusercontent.com/79877349/114323508-6603b880-9ada-11eb-88c6-f770e352d69f.png)

* School Summary 
*       
When we look at the school summary, almost nothing changed with the exception of Thomas High School. There was a significant change in passing percentages for that school.
![school summary old](https://user-images.githubusercontent.com/79877349/114323515-6ef48a00-9ada-11eb-9528-889dfbd28fc2.png)
![school summary new](https://user-images.githubusercontent.com/79877349/114323519-71ef7a80-9ada-11eb-88fd-d96a8a9ce5b4.png)

* Changing Overall Percentage
*       
When we changed the scores of  the Thomas High School 9th graders to NaN it affected the overall passing percentage of the school also very little. 
![Overall percentage old](https://user-images.githubusercontent.com/79877349/114323533-8764a480-9ada-11eb-81c2-15cd176548f6.png)

## Replacing 9th Grade Scores


* Math and Reading Scores by Grade
* 
These are the updated math and reading scores. You will notice the (NaN) shown on the 9th grade Thomas High School scores.
![9th grade math new](https://user-images.githubusercontent.com/79877349/114323765-a152b700-9adb-11eb-93fc-f0b2b8ad6eeb.png)
![9th grade reading new](https://user-images.githubusercontent.com/79877349/114323770-a3b51100-9adb-11eb-9d63-b6bd25b27e28.png)

* Scores by School Spending
* 
Looking at the spending summary, the analysis uncovered a change in the math, reading, and overall categories.
![school spending new](https://user-images.githubusercontent.com/79877349/114323796-cc3d0b00-9adb-11eb-945a-b5a2adeeae71.png)

* Scores by School Size
* 
Here, we have a school size analysis. We can see that there is a significant decrease across the board for bigger schools.
![school size new](https://user-images.githubusercontent.com/79877349/114323811-d8c16380-9adb-11eb-9126-e8fae3d7b035.png)

* Scores by School Type
* 
    We can also see that, according to school type, the score were also across the board better for “Charter Schools” rather than in the “District”
    ![school type](https://user-images.githubusercontent.com/79877349/114323822-e545bc00-9adb-11eb-91eb-3295b75995d8.png)

                                                                                            

## Summary
Math and reading scores by grade remained the same with the exception for Thomas high School which had reported they had no data to report.

Scores by school spending changed at the $630-644 range: -percentage passing math dropped from 73% to 67% thus the percentage passing reading dropped from 84% to 77% which created an overall passing percentage drop from 63% to 56%.

Scores by School size changed at the medium (1000-2000) size -percentage passing math dropped from 94% to 88%-percentage passing reading dropped from 97% to 91%-overall passing percentage dropped from 91% overall passing percentage dropped from 91% to 85%.

Scores by school type changed by Charter school type: - percentage passing math dropped from 94% to 90% -  percentage passing math dropped from 97% to 93% - overall passing percentage dropped from 90% to 87%.  

