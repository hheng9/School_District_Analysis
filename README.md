# School_District_Analysis

## Overview of The School District Analysis
### The purpose of this analysis was to collect the data, prepare the data, and analyze the data through multiple grade levels, students, school types, and scores. We filter the necessary data as requested by using tools such as Python, Jupyter Notebook, and Anaconda to pull the supplied CSV file information to gather the correct results as requested. Jupyter Notebook allows us to pull data from the Pandas library to clean, manipulate, and visualize all the data without altering the original dataset. Pandas lets us work with two different data types in the form of a series dataset or dataframe dataset. 

## School District Analysis Results
### Collecting the Data
We began our analysis by importing Pasndas and the OS function by setting the read function to the supplied CSV path then verifying the data was imported correctly by generating the top 5 results ("head()").

![importCSV](https://user-images.githubusercontent.com/118647523/210295208-ca87097e-9015-4a33-81a4-8ef1b23d9291.png)

## Prepping the Data
After importing our file we needed to clean up the data to remove all unecessary information for better accesiblility. By doing so we needed to remove or drop missing values, NaN values, duplicate rows, unwanted suffix, and understanding or changing data types to possible float/integers.

![drop1](https://user-images.githubusercontent.com/118647523/210296414-343ff043-7ab1-4b1f-8b68-f2903145f549.png)![drop2](https://user-images.githubusercontent.com/118647523/210296424-10239fee-86b2-40db-958c-f843129a1f10.png)![types1](https://user-images.githubusercontent.com/118647523/210296436-e8c852d0-0b28-44e6-a511-552332752eb1.png)![types2](https://user-images.githubusercontent.com/118647523/210296667-55274862-1edd-40a5-a457-e56e147fe29b.png)

![duplicate](https://user-images.githubusercontent.com/118647523/210296429-bb3353ba-18db-4250-94f8-b8b7b620d1d1.png)

![int1](https://user-images.githubusercontent.com/118647523/210296447-cf51d954-33e6-4937-8813-eca7847ee603.png)![int2](https://user-images.githubusercontent.com/118647523/210296450-6e93d4c1-0292-4148-a4ac-05e9bd21c224.png)

## Summarizing the Data
We can generate data counts, averages, deviations, min/max values by performing the describe function as listed below. With the correct code I was able to gather the average math scores and minimum reading scores as requested. 

![describe](https://user-images.githubusercontent.com/118647523/210297158-9a326613-3b4d-4e43-baa5-4050f0ea8adb.png)

## Specified Data
I performed the location and index location function to pull up specific schools, scores, and grades. We are able to collect the assigned data to view describe data in grade 9, minimum overall reading scores, and all reading scores from the 10th grade. This makes is cleaner to view the desired information and filter out and unwanted data.

![specific2](https://user-images.githubusercontent.com/118647523/210297854-82a1c9da-5d42-4020-ba17-15ae6d385501.png)![specific1](https://user-images.githubusercontent.com/118647523/210297857-f1230e6d-0bf9-4c04-ba2a-c9d8132f32b2.png)

![specific3](https://user-images.githubusercontent.com/118647523/210297859-b3da4f8e-8be3-4cc3-8269-74f576589bbf.png)

![specific4](https://user-images.githubusercontent.com/118647523/210297868-33db43ac-408b-43b2-8855-d6a8c2cac31d.png)




