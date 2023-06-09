# pandas_challenge

#Description
This project is meant to demonstrate how pandas can be used with python to analyze data. Specifically, the data for this project is from a city’s school district and is analyzed in order to help the school board and mayor make strategic decisions about priorities and budgets. The raw data has each student’s math and reading scores, the school they attend, and school specific information. 

The code is designed to summarize the following metrics for each school in the district, school name, school type, total number of students, total budget for the school, the budget per student. Average math score, average reading score, the percentage of students how passed math, the percentage of students who passed reading, and the overall percentage of students who passed both subjects. 

Furthermore, the code calls out which schools are the highest preforming by sorting the data by percentage of overall passing rates and saving this data to a DataFrame. The lowest preforming schools are also sorted by percentage of overall passing rates and saved to a separate DataFrame. 

To better understand which students might need additional support, the data is parsed into math scores by grade and reading scores by grade. Then to help understand what type of school needs the most support to raise test scores the data is first binned into school spending ranges, school size, and school type. 

# PyCity Schools Analysis
There are 15 schools included in the analysis for this district. When looking at the summary data, specifically the data that has been binned there are clear differences in overall passing rates. When the data is binned by school size the largest schools (2000-5000) students have the lowest passing rates (59.73% passing) compared to the much higher passing rates of small (<1000 students) (90.53% passing), and medium (1000-2000 students) (90.69%) school. Another result of note is that the overall passing rate for charter schools is 91.44% compared to 55.12% for district schools. With the difference in passing rates being so large, it is important to consider solutions, especially when considering future budgets. However, when the overall passing rates are binned by budget, the lowest preforming group of schools are actually the schools with the highest budget of $645-680 per student and an overall passing rate of 55.12%. With these results in mind, I recommend looking at other solutions for increasing passing rates other than increasing the budget for the lower preforming schools. Further analysis could look at the differences between the charter and district school, and the differences in how the large versus medium and small schools are operated. Unfortunately, this analysis cannot be performed at this time without additional data. 

#Installation
For this code you will need to: 
import import pandas as pd

#Usage
I ran the code in jupyter notebook. 

#Support
If help is needed with python, I recommend searching Stack Overflow for the answers to specific questions.  

#Authors and acknowledgment
This code was completed by Kelsey Brantner. The following link was referenced to learning about indexing when creating a DataFrame, https://stackoverflow.com/questions/38222538/how-to-create-a-dataframe-from-dictionary-with-auto-increment-index. The following link was referenced to help increase my understanding of how to bin data by a specific column and how to label that binned data, https://stackoverflow.com/questions/45273731/binning-a-column-with-pandas. 

#License
According to the files’ source site, “Data generated by Mockaroo, LLCLinks to an external site., (2022). Realistic Data Generator. Data for this dataset was generated by edX Boot Camps LLC, and is intended for educational purposes only..”

#Project status
At this time the project is considered complete since the data that would facilitate further analysis is not currently available. 


