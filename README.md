# School_District_Analysis

## Overview of The School District Analysis
### The purpose of this analysis was to collect the data, prepare the data, and analyze the data through multiple grade levels, students, school types, and scores. We filter the necessary data as requested by using tools such as Python, Jupyter Notebook, and Anaconda to pull the supplied CSV file information to gather the correct results as requested. Jupyter Notebook allows us to pull data from the Pandas library to clean, manipulate, and visualize all the data without altering the original dataset. Pandas lets us work with two different data types in the form of a series dataset or dataframe dataset. 

## School District Analysis Results
### Collecting the Data
We began our analysis by importing Pasndas and the OS function by setting the read function to the supplied CSV path then verifying the data was imported correctly by generating the top 5 results ("head()").
### head() function displayed
![importCSV](https://user-images.githubusercontent.com/118647523/210295208-ca87097e-9015-4a33-81a4-8ef1b23d9291.png)

## Prepping the Data
After importing our file we needed to clean up the data to remove all unecessary information for better accesiblility. By doing so we needed to remove or drop missing values, NaN values, duplicate rows, unwanted suffix, and understanding or changing data types to possible float/integers.
###
![drop1](https://user-images.githubusercontent.com/118647523/210296414-343ff043-7ab1-4b1f-8b68-f2903145f549.png)![drop2](https://user-images.githubusercontent.com/118647523/210296424-10239fee-86b2-40db-958c-f843129a1f10.png)
### Column Types
![types1](https://user-images.githubusercontent.com/118647523/210296436-e8c852d0-0b28-44e6-a511-552332752eb1.png)![types2](https://user-images.githubusercontent.com/118647523/210296667-55274862-1edd-40a5-a457-e56e147fe29b.png)
![duplicate](https://user-images.githubusercontent.com/118647523/210296429-bb3353ba-18db-4250-94f8-b8b7b620d1d1.png)
### "th" suffix is removed
![int1](https://user-images.githubusercontent.com/118647523/210296447-cf51d954-33e6-4937-8813-eca7847ee603.png)![int2](https://user-images.githubusercontent.com/118647523/210296450-6e93d4c1-0292-4148-a4ac-05e9bd21c224.png)

## Summarizing the Data
We can generate data counts, averages, deviations, min/max values by performing the describe function as listed below. With the correct code I was able to gather the average math scores and minimum reading scores as requested. The overall math score came out to 64.67% and a minimum reading score of 10.5.
### Summary statistics
![describe](https://user-images.githubusercontent.com/118647523/210297158-9a326613-3b4d-4e43-baa5-4050f0ea8adb.png)
### The mean of the "math_score" and min "read_score"
![summarizing](https://user-images.githubusercontent.com/118647523/210482970-f69e7797-1019-4ce1-ac8a-efebee135c83.png)

## Specified Data
I performed the location and index location function to pull up specific schools, scores, and grades. We are able to collect the assigned data to view describe data in grade 9, minimum overall reading scores, and all reading scores from the 10th grade. This makes is cleaner to view the desired information and filter out and unwanted data. Matthew Thomas from Dixon High School had the lowest reading score from all the schools. Dixon High is a charter school with a 95.3 high for their reading scores. The average between 11th and 12th grade reading scores came out to around 75%.
### Grade columns 
![GradeColumn](https://user-images.githubusercontent.com/118647523/210484336-23416349-3736-440b-bd40-75c919866623.png)
### The first three rows of Columns 3, 4, and 5
![specific1](https://user-images.githubusercontent.com/118647523/210484416-ea32201e-8da3-4ed1-ba73-610e9af2a353.png)
### The summary statistics for 9th graders
![specific4](https://user-images.githubusercontent.com/118647523/210484504-47a6eca2-5f24-480c-b939-ebfe89bef7e9.png)
### Minimum reading score
![specific3](https://user-images.githubusercontent.com/118647523/210484576-8ad3d356-07bd-4a2f-b1ed-586f4cafb03a.png)
### The reading scores of the 10th graders at Dixon High School
![specific2](https://user-images.githubusercontent.com/118647523/210297854-82a1c9da-5d42-4020-ba17-15ae6d385501.png)!
### The average reading score of all the students in Grades 11 and 12 combined
![11-12_avg_read](https://user-images.githubusercontent.com/118647523/210484766-b9bc7934-4af1-4395-b1f0-0422be53f670.png)

## Difference Bewtween District and Charter Schools
As we can tell from the data collected Charter schools performed slightly better in their reading scores and their math scores. Motogomery High School has the highest population of students attending their school with Chang High School having the least amount of students attending their school. The average math score is higher in the earlier years of the charter schools but is more consistant throughout all the grades in public schools.
### The average reading and math scores for school types
![comparison2](https://user-images.githubusercontent.com/118647523/210485019-94e95c7e-7f67-4ddd-a8ee-f9534c5bcff9.png)
### The total number of students per school
![comparison1](https://user-images.githubusercontent.com/118647523/210298703-d4f0392c-4630-490c-b4be-61c39d76fbdf.png)
### Average math scores for school types and grade levels
![comparison3](https://user-images.githubusercontent.com/118647523/210481514-a83659a5-766a-45cb-8ebe-c023a54b01d6.png)


## Summary of Data
 * The overall math score came out to 64.67% and a minimum reading score of 10.5.
 * Matthew Thomas from Dixon High School had the lowest reading score from all the schools.
 * Dixon High is a charter school with a 95.3 high for their reading scores. 
 * The average between 11th and 12th grade reading scores came out to around 75%.
 * Charter schools performed slightly better in their reading scores and their math scores.
 * Motogomery High School has the highest population of students attending their school.
 * Chang High School having the least amount of students attending their school.
 * The average math score is higher in the earlier years of the charter schools.
 * The average math score is more consistant throughout all the grades in public schools.
 * The average math score is higher in the earlier years of the charter schools.

