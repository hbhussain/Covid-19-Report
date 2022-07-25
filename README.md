# Covid-19-Report 2020-2022 Report
Report Analysis for Global Covid19 Infections

#  Problem Statement
COVID-19 is caused by a coronavirus called SARS-CoV-2. Older adults and people who have severe underlying medical conditions like heart or lung disease or diabetes seem to be at higher risk for developing more serious complications from COVID-19 illness (CDC). Questions to be answered are ;
i. Total numbers of confirmed cases, death cases and Recovered cases.
ii. Top 5 Countries with the highest number of Covid 19 infection (Confirmed cases)
iii. Five (5) countries with less confirmed cases
iv. Top five(5) countries with highest covid 19 fatality(death) 

# Data Sourcing
Data used in this analysis is obtained from https://github.com/CSSEGISandData/COVID-19/tree/master/csse_covid_19_data

# Data Cleaning 
## Step 1
The data is imported using excel web scrapping ![fromweb](https://user-images.githubusercontent.com/30692271/180700480-bb51cbed-5162-48a6-8671-ec7ed8a8d18a.JPG)
Click on get data from web and it will take you to the next image

![copylink](https://user-images.githubusercontent.com/30692271/180700536-2caa83e8-621b-4376-bf6a-3606d65fe804.JPG)
Copy the link in address bar and paste in the box

![pastelink](https://user-images.githubusercontent.com/30692271/180700547-61ced9ec-b3cd-43db-899f-26db0a208315.JPG)![transform]
Click ok to continue


![transform](https://user-images.githubusercontent.com/30692271/180701183-bc9030a0-b448-43ee-b833-ce10e09d0c7b.JPG)
Click transform to transform your data
Here the cleaning and manupulating of the dataset begin. The dataset contain so many columns which can be difficult to deal with, so unpivoting the column will staked other columns and make analysis easier. After that making first column as header to get rid of what the query suggested as header. Removing null or empty cells, removing duplicate and trimming extra spaces in the dataset is carried out. The dataset are three in number confirmed cases, death cases and recovered. The three dataset are merged to become one dataset using mergequeries function in power query using 3 coloumn field. 



# Finding & Recommendations
1. United States tops with the highest confirmed cases and death 
2. South and North korea has the lowest confirmed and death cases
3. India has the highest number of covid19 infection recoveries.
4. Covid 19 infection spiked from 2020 - 2022 

