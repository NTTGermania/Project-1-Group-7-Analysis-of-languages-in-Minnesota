# Languages Spoken in the Homes of Minnesota Public School Students
## Project 1 for the University Of Minnesota Data Visualization and Analytics Boot Camp
### **Contributors: Sam Espe, Yameena Khan, Maryam Osman, Nhan Tran (Group 7)**

## Topic Overview
Minnesota is home to hundreds of thousands of families who speak dozens of distinct languages. Minnesota's Department of Education gathers data on the families of public school students every year, including what language students speak at home. This data is publicly available for the school years 2006-2007 to 2021-2022.
We used this data to examine the proportions of families that speak a language other than English at home, the distribution of non-English-speaking families across the State of Minnesota, and how the most frequently spoken languages change in that time period.
<br />

## Research Questions and Motivations
The members in our group all speak multiple languages. This led us to be curious about how many Minnesota families speak non-English languages, and how that has changed over time.
We developed the following research questions:
* How many unique languages are spoken in the homes of public school students in Minnesota between 2007 and 2022?
* How has the  distribution of languages changed over the interval of 2007 to 2022?
* Which languages, excluding English, are the most common in Minnesota?
* How are the number of students who speak a given non-English language distributed geographically, and how does that change over time?

## Data Exploration and Clean-Up Process
The data we downloaded from Minnesota's Department of Education's website was in Excel format, which we converted into CSV form and read them in our Jupyter Notebook. The data was cleaned and standardized, making sure we have uniform column headings, all the redundunt/repeat values were removed. Tests were done to check and ensure we had all and only the unique languages in our dataset.
At the end of the clean up process, we found 350 unique languages. This indicates that across the State of Minnesota, 349 unique languages other than English are spoken.

## Data Analysis Process
To do the analysis, we ran a few different tests and presentations on the data:
* **Hypothesis Testing** <br />
    Our hypothesis is that Minneapolis & Saint Paul, the 7-county metro area (excluding Minneapolis & Saint Paul), and outstate  Minnesota have different mean number of students that speak non-English languages from 2007 to 2022.
* **Linear Regression**<br />
    We decided to create a linear regression on the proportion of families that speak non-English languages, to see how that proportion changes over time. We used this linear regression to predict the proportion of non-English-speaking families in the years 2025 and 2030.
* **Bar graphs**<br />
    We decided to compare the number of languages spoken per strata from 2007 to the languages spoken per strata from 2022 using Bar graphs.
* **Line Graphs**<br />
    We decided to see view the trends of the number of unique languages over time for each strata using one line graph that has all trends through 2007 to 2022 for all statas.
* **Pie Charts**<br />
    We decided to use pie charts to compare the proportion of students speaking English at home with the proportion of students speaking languages other than English.

## Conclusions
As per our analysis we made the following findings:
* The number of students speaking unique languages over the period of time has been increasing. This could be an indication of diversity increasing in the state of Minnesota
* The number of unique languages spoken by students in school districts is different depending on where the school districts are geographically across the state.
* Our linear regression predicts that in 2025, about 19% of Minnesota households will speak non-English languages at home, and by 2030, that proportion will be about 21%.
