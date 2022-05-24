# Folashade_Portfolio
Data Analytics Portfolio

# [Project 1: Data-Analytics-Course-Project](http://localhost:8888/notebooks/Wikipedia%20Project%20-%20AfroFem%20Coders.ipynb)
For the project, you are provided with a dataset to analyze using the skills learned in the course.When working on the project, you are encouraged to consider the different stages of the data life cycle and the importance of using the right tools to efficiently answer as many of the project questions as you can. Feel free to be creative in how you present your findings to answer each project question. At the very minimum, you are expected to create a dashboard in Tableau Public with at least 3 different visualizations to help answer some of the project questions.
## Dataset description:
The dataset contains the daily number of webpage visits for several Wikipedia webpages. (if you are not familiar with Wikipedia, you can check it out here https://en.wikipedia.org/wiki/Main_Page). The dataset includes daily page visit counts for 1,500 Wikipedia pages starting on 2016-01-01 until 2016-12-31.
Dataset source: Kaggle.com
## Project Questions:
1. what were some of the most trending search topics on Wikipedia on the following days? Using the provided dataset, can you show some evidence to support your answer? 
a- New year's day 
b- November 8, 2016
2. Which page experienced the biggest decline in page visits during 2016?
3. Which page experienced the biggest increase in page visits during 2016?
4. Wikipedia pages could be written in several languages. How many languages are represented in this dataset? What proportion of the pages does each language represent? 
- Hint: One may infer which language a page is written in based on the page name
e.g. Special:Search_fr.wikipedia.org_all-access_all-agents is written in French and Special:Book_en.wikipedia.org_all-access_spider is written in English.
5. Based on the provided dataset, which day(s) of the week is/are the most popular for visiting wikipedia?
6. Based on the provided dataset, which day(s) of the week is/are the least popular for visiting wikipedia?
7. Based on the dataset provided, which device type is used more frequently for visiting wikipedia i.e. desktop or mobile devices?
- Hint: For some of the pages in the dataset, it is possible to distinguish whether the visits to the page came from a desktop or a mobile device.
For example, consider Barack Obama's wikipedia page:
* Barack_Obama_en.wikipedia.org_desktop_all-agents : these visits came from desktop devices.
* Barack_Obama_en.wikipedia.org_mobile-web_all-agents: these visits came from mobile devices.


# [Project 2: Introduction to SQL with DataCamp](http://localhost:8888/notebooks/Desktop/Adunni%20Data/Project%20Notebook%20Codes/project/Introduction%20to%20DataCamp%20Projects/notebook.ipynb)
Analysing with Jupyter Notebook
## Project Questions
1. It's estimated that on average 256 children were born every minute in 2016. The code cell below calculates how many children were born on average on a day.
2. Using the greet function, run a code to show your first_name and last_name
3. Connect to a PostgreSQL database that has a table that contains country data, then inspect the first three rows of the table by putting %%sql ahead of the SQL commands (more on the meaning of %% later).
4. Run a code to select the row in the countries table for Belgium
5. Convert the SQL results in question 4 to a pandas DataFrame! Let's convert the entire countries table.
6. Run the last query we just ran except after connecting to and querying the database using SQLAlchemy.
7. Using the previously created pandas DataFrame that we named df, let's plot the number of countries in each continent as a bar chart using the plot() method of pandas DataFrames.


# Project 3: [Data Analytics on Excel Capstone Project](https://docs.google.com/spreadsheets/d/166fDijPgtf-cRz_30nozBKRS_PVHT6y0NbAMBhzGDds/edit#gid=743487262)
## Question 1
Using Sales Data 1
1. Extract sales made from Kentucky, California and Florida under furniture and office Supplies (Also show their corresponding order id, order date, Ship Date, Customer name, Sub category and product name)
2. For all kinds of Xerox products, extract their respective sales and customer names
3. Find the average total sales for (question 2) if sales is not equal to 500
4. For the customers names in (question 2), split it to first and last name (dont use flash fill and text to column)
5. Find the total sales for each of the Ship modes
6. Find the average sales for each of the Regions

# Project 3: [Data Analytics on Excel Capstone Project](https://docs.google.com/spreadsheets/d/1gUGLRjS7s3VfVT7GcOf7IjnqU_53V6yb/edit#gid=1297590760)
## Question 2
Use dataset 1 for the following:
1) Is there an outlier in the Sales recorded ($)? (Show your procedures)
2) On a new sheet,
a) Generate top 20 highest Sales, then use VLOOKUP to generate their respective item number id, Average Inventory on Hand ($), In-Stock % and Week ID.
b) What is the average sales for the top 20 highest Sales?
3) On a new sheet,
a) Generate top 20 lowest Sales, then use VLOOKUP to generate their respective item number id, Average Inventory on Hand ($), In-Stock % and Week ID.
b) What is the average sales for the top 20 lowest Sales?

# Project 3: [Data Analytics on Excel Capstone Project](https://docs.google.com/spreadsheets/d/1gcEoVgUqbwpFGk0PiG2EjHwBaI7evCPl/edit#gid=2144271039)
## Question 3
Use dataset 2 for the following:
1) Create a new column to know if a course is free or paid, note; if price is 0,then the course is free, otherwise its paid.
2) What is the price, number of subscribers, number of reviews, number of lectures, level, rating, content duration, subject, free or paid for the following course titles:
FOREX: From Zero To Hero
Forex Trading Masterclass - Learn To Trade Better
Aprenda a Investir seu Dinheiro
Visualizing Data
CPA 10 COMPLETO
Innovators and innovation: Travel through time!
Intermediate Accounting 1: Easy. Fast. Simple!
Numeracy skills in business and everyday life:Think and Deal
Learn the Forex Naked Price Action Pogo Trade
Rails Ecommerce App with HTML Template from Themeforest
ASP.NET MVC 5 Project - Facebook Clone
Creating Custom Web Maps
Learn Reactivex From Ground Up
Introduction to web programming for GIS applications
Learn Web Animation the Easy Way: An Intro to SVG and GSAP
Introduction to QGIS Python Programming
PHP Specialist (2017 Edition)
HTML/CSS Bootcamp


# Project 4: [From Epidemic to Pandemic](https://app.datacamp.com/workspace/w/759857f5-9727-4c2a-bc66-8f1c6900d34e/edit)
In December 2019, COVID-19 coronavirus was first identified in the Wuhan region of China. By March 11, 2020, the World Health Organization (WHO) categorized the COVID-19 outbreak as a pandemic. A lot has happened in the months in between with major outbreaks in Iran, South Korea, and Italy.

We know that COVID-19 spreads through respiratory droplets, such as through coughing, sneezing, or speaking. But, how quickly did the virus spread across the globe? And, can we see any effect from country-wide policies, like shutdowns and quarantines?

Fortunately, organizations around the world have been collecting data so that governments can monitor and learn from this pandemic. Notably, the Johns Hopkins University Center for Systems Science and Engineering created a publicly available data repository to consolidate this data from sources like the WHO, the Centers for Disease Control and Prevention (CDC), and the Ministry of Health from multiple countries.

In this notebook, you will visualize COVID-19 data from the first several weeks of the outbreak to see at what point this virus became a global pandemic.
