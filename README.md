# Basic EDA: Yellow Taxi New York City Trip in April 2020
This mini project is part of independent learning progress i made. 

## Mini Project Intro
The purpose of creating this mini project is to perform simple approach to do Exploratory Data Analysis using Python. Methods used are basic, so it's beginner friendly. I also add comments and explanation, to help others understand my work easily. Instead solving any business problem, i choose to extract meaningful insight from raw data set, that's why i focus answering questions to fulfill my curiosity.

## Data set Used
The data set obtained from Pacmann AI Mini Course entitled "Intro to Data and Analytics". Unfortunately, the data set show only Yellow Taxi Trip records in April 2022 and it contains only 1000 records which taken as sample with 17 variables. Visit [this link](https://www1.nyc.gov/assets/tlc/downloads/pdf/data_dictionary_trip_records_yellow.pdf) to access data dictionary.

## Python Packages
* Pandas
* NumPy
* Seaborn
* Matplotlib
* Math

## Methods Used
* Data Cleaning

23 Missing value in 'passenger_count', 'RatecodeID', 'congestion_surcharge', and 'airport_fee' are handled by filling them with each variable's median, because they're not normally distributed.
* Data Wrangling

I calculated trip duration and trip speed by convert dtype from object to datetime in "YYYY-MM-DD HH:MM:SS" format, and then into unix timestamp.
Duration were calculated by substracting duration_drop with duration_pickup, meanwhile speed were calculated by dividing trip distance with trip duration. To easier visulization, i aggregate clean data in daily and weekly basis. 

* Data Visualization

This method is part of Exploratory Data Analysis, there are 2 categories of EDA:
(1) Non-graphical methods to calculate statistics summary, and Graphical methods to summarize the data in pictorial way
(2) Univariate methods to look at one variable, and Multivariate methods to explore relationship of 2 or more variables

## Exploratory Data Analysis
1. Calculate total passenger, revenue, fare amount, and tip amount in April 2022
2. Calculate average trip distance, duration, and speed in April 2022
3. Calculate total additional fare in April 2022
4. What's the most used payment method?
5. How's the passenger satisfication rate?
6. What's the most used VendorID?
7. Draw Line Chart of Daily Trip Count, Total Daily Revenue, Average Daily Distance, Passenger Count, Average Daily Duration, Average Daily Speed and Average Daily Fare!
8. Draw stacked bar chart of Weekly Trip Count, and Passenger Count (y-scale in hundreds)!
9. Draw grouped Bar Chart of Average Weekly Distance, Average Weekly Trip Duration, and Average Weekly Speed (y-scale in hundreds)!
10. Which week in April 2022 has the highest revenue?


_Have a read!, I'm looking forward to your feedback._
