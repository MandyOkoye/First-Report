# INTRODUCTION
![EXCEL WORK STATION](https://github.com/MandyOkoye/First-Report/assets/135643020/9f2465c6-7c11-4697-ad32-106344e04131)

While on my learning jourmey with https://github.com/Datafyd i was given this dataset for mary's pharmacy sales from 2014-2019, i was asked to anyalse the dataset to determine and identify trends and petterns in the sales of pharmaceutica drugs sold over time, i will also visualize the dataset on a dashboard to fimd out insights to anser the following statement of problems

# BUSINESS PROBLEM

Mary is the owner of a small pharmacy located in a busy city center. She has been running the pharmacy for the past few years and has noticed that sales have stagnated. Despite the competitive pricing, Mary's Pharmacy has struggled to attract new customers.

To try and improve her business, Mary decided to contact Datafied Technologies to conduct a thorough analysis of her sales data using the transactional data collected over the past 6 years. She exports the data from her Point-of-Sale system, which includes information on the date and time of each sale, the name of the pharmaceutical drug sold, and the quantity of each drug sold.

As the senior data analyst at Datafied Technologies. i am required to come up with business questions and generate metrics that could be tracked to identify trends and patterns in the sale of pharmaceutical drugs sold in the pharmacy over time. i also need to visualize the data and create dashboards to uncover hidden insights and track the metrics you have defined for the business.

Mary needs @Datafyde"s help to uncover valuable insights about her business and take action to improve its performance. Mary intends to use this newfound knowledge to make informed decisions about her inventory and marketing strategies, ultimately leading to an increase in sales and the growth of her business

# DATASET INFORMATION.

i have downladed the CSV file sent to me and i have gone ahead to clean the dataset.
the file has 9 columns and 50533 rows on one sheet.

The dataset is built from the initial dataset consisting of transactional data collected in 6 years (period 2014-2019), indicating the date and time of sale, pharmaceutical drug brand name, and sold quantity, exported from the Point-of-Sale system in the individual pharmacy. The selected group of drugs from the dataset (57 drugs) is classified into the following Anatomical Therapeutic Chemical (ATC) Classification System categories:

M01AB - Anti-inflammatory and antirheumatic products, non-steroids, Acetic acid derivatives, and related substances

M01AE - Anti-inflammatory and antirheumatic products, non-steroids, Propionic acid derivatives

N02BA - Other analgesics and antipyretics, Salicylic acid and derivatives

N02BE/B - Other analgesics and antipyretics, Pyrazolones and Anilides

N05B - Psycholeptics drugs, Anxiolytic drugs

N05C - Psycholeptics drugs, Hypnotics, and sedatives drugs

R03 - Drugs for obstructive airway diseases

R06 - Antihistamines for systemic use

[saleshourly.csv](https://github.com/MandyOkoye/First-Report/files/12165746/saleshourly.csv)   my dataset

# PROJECT OBJECTIVE

The objective is to generate metrics that could be tracked to identify trends and patterns in the sale of pharmaceutical drugs sold in the pharmacy over time. by analyzing transactional sales data and then visualizeing the data and create dashboards to uncover hidden insights and track the metrics.

# UNDERSTANDING THE BUSINESS OBJECTIVES AND USER REQUIREMENT.

I dived in to understand the business specific requirement and objectives from the business problems, i was able to identify key areas to focus on the business questions the business need answers to.

# BUSINESS QUESTIONS

Based on the discussions in Step 1, i have defined specific business problems the dashboard should answer. Example questions include:

What is the overall sales trend for the pharmacy?

Which drugs have the highest sales revenue?

Are there any seasonal sales pattern for specific drugs or ATC category? 

What time of the day has the highest sales?

# KPI"s

Total sales revenue

Total quantity sold

Sales growth rate

Top selling drug by drug category and season

Highest quantity sold by drug category

# PREPROCESSING THE DATA

The data was clearned by removing duplicates, inconsistences and ensuring the data is in a suitable format for analysis.

# DATASET BEFORE CLEANING

![1690398218284](https://github.com/MandyOkoye/First-Report/assets/135643020/41077e02-5f2b-44d1-a393-4d74fefcd715)


# DATASET AFTER CLEANING

![powerbi after cleaning](https://github.com/MandyOkoye/First-Report/assets/135643020/687300dd-bb20-476d-bac6-b81653619aca)


# DATA MODELING AND RELATIONSHIPS

I identified the necessary dimentions to break down the table, which are 

Drug table

Time table

Date table

i conected all my tables using the star schema in a one to many relationship.

![powerbi relationships](https://github.com/MandyOkoye/First-Report/assets/135643020/6dfc22d3-ebf8-417e-bcd0-f23f7a494594)


Appoprate charts were used eg donout chart, clusterd colum chart, bar chart, cards, slicers etc to represent the metrics and insights and aslo to give detailed information.

![powerbi dashboard](https://github.com/MandyOkoye/First-Report/assets/135643020/b0e945ae-b2ad-4f55-ad3e-65d395e7006a)


The report shows that Mary's pharmacy saw a lot of downtime especially in 2015, 2017 and 2019. sales rate was inconsistent across the seasons in the different years, the most sales are made in the afternoon.

The top selling drug kept fluctuating across all parameters (season, month, year) but it is noticed that  M01AB, N0SC and M01AE drug category did the generated the least sales across parameters.

2018 showed the highest sale recorded.

The NO5B drug category generated the highest sales probablky because of the price it is sold at but the NO2BE category had the highest quantity sold.

The 'NO' drug category did well across all seasons but highest in autunm and spring,quantity sold for MO category seemed to increase in summer.
Afternoon saw more sales across all category followed by morning.

# RECOMENDATIONS

Mary's pharmacy should therefore look into reducing stock on the the said NOSC and MO1AE and futher increase stock on N05B, NO2BE, R03 and R06.

Mangement should consider increaseing price on NO2BE as it shows high quantity sales but low revenue.

Drugs that showed seasonal pattern should be made readily avalable durring it's season.

# INTERACT WITH MY DASHBOARD HERE

https://app.powerbi.com/view?r=eyJrIjoiOWQzZWYyMDUtNWY3ZC00YWE2LWFhMTYtZTNhZDgzMDZkMDBkIiwidCI6ImRhMWM0NzgzLTFhYjEtNDVhOS1iYmQ3LWVhNTkzZmQ0ZWE3ZiJ9


