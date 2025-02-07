
# Goodcabs Performance Analysis
## Project Background:
This project focuses on analyzing the performance of Goodcabs, a cab service company committed to supporting local drivers and providing excellent service to passengers in tier-2 cities across India. Goodcabs has ambitious growth targets for 2024, aiming to increase ridership and improve passenger satisfaction. To achieve these goals, the company needs a data-driven approach to understand its current performance and identify areas for improvement.
This analysis will focus on key metrics such as Total trips, total distance traveled, average trip distance, and trip type (new vs. repeated),  Total fare (revenue), average fare per trip, and average fare per km, Average passenger rating, driver rating. The insights generated from this analysis will be crucial for informing strategic decision-making across various departments, including Operations, Marketing, Product, and Finance.
By providing actionable recommendations, this project aims to enable Goodcabs to optimize its operations, enhance customer experience, and achieve its ambitious growth targets.
## Executive Summary:
### Revenue Growth:
Goodcabs generated a total revenue of 108M from 426K trips, exceeding 99% of its trip target. February is the highest revenue generated with 20M and lowest in June by 15M and it shows a decreasing trend for a period of six months.
### Repeat Customer Rate: 
Repeat customers contributed significantly to revenue, accounting for 58% of all trips. The repeat passenger rate (RPR) steadily increased from 19% in January to a high of 33% in May. Surat emerges as the leading city with the highest repeat customer rate of 43%. 
### City-Level Variation:
Top Performers: Jaipur emerged as the top-performing city in terms of revenue with 37 Million contributing 34% across all cities.
Underperformers: Cities like Mysore, Vadodara, and Coimbatore underperformed in terms of revenue with 4M flat across these cities.
### Seasonal Trends:
Trip demand exhibited seasonal fluctuations, with peak demand observed in February for cities in the northern region and during April-May for cities in the southern and western parts of India.
### Target Analysis:
With targeted trips of 429K over a course of six months, it has achieved 426K total trips and achieved 99% of the target. In terms of a new passenger target of 185K in a period of six months, 177K new passengers were acquired by Goodcabs and  achieved 96% of the new passenger target. Some cities, including Jaipur, fell short of their new passenger acquisition goals.
### Passenger Satisfaction:
Top Performers: Mysore, Jaipur, and Kochi consistently demonstrated high passenger ratings.
Underperformers: Cities like Surat, Lucknow, and Vadodara required improvement in this area with the lowest average passenger ratings.
## Data Model

### Trips database:
This database contains both detailed and aggregated data on trips, passenger types, and repeat trip behavior for Goodcabs' operations across tier-2 cities. It organizes trip data by city, month, and day type (weekday or weekend), enabling comprehensive analysis of travel patterns, passenger demographics, and repeat usage trends.
### Targets database: 
This database holds Goodcabs' monthly targets for each city, including goals for trip counts, new passenger acquisition, and average passenger ratings. It enables performance evaluations against key benchmarks set by the company.

The raw dataset consists of 426000 rows.

![image alt](https://github.com/SUNNY-GAWANDE/Operational-Analytics-on-Goodcabs/blob/main/datamodel.png?raw=true)

## Overview

![image alt](https://github.com/SUNNY-GAWANDE/Operational-Analytics-on-Goodcabs/blob/76e38990f4ece5a01ff51e13b50f82ef54894659/Overview_1.png)

### KPI Performance: 
During the 6 month period Good Cabs has earned 108M revenue from 426K total trips by 238K passengers and average trip cost to 254. From 426K total passengers, 177K(42%)  were new passengers and 249K(58%) were repeat passengers. Repeat rates were higher compared to new passengers. 
### Revenue by City: 
Jaipur city generated the highest revenue with 37M, contributing to 34% overall. Second city in terms of revenue is Kochi, generating 17M and contributing 15.7%.
Bottom 3 cities are Mysore, Vadodara & Coimbatore, generating 4M revenue which is flat across all three cities and contributing to only 3-3.5% in overall revenue. 
### Revenue by Month: 
In terms of revenue, January generated a revenue of 18M and it increased further to 20M in the month of February which is the highest revenue for Goodcabs. However, revenue fell for the next two months and it was reduced to 17M in April. Revenue has increased slightly in the month of may to 18M but it falls rapidly to 15M in June month which is lowest revenue among six months.  Overall it shows a decreasing trend. 
### Total Trips by Revenue: 
As the number of trips increases the revenue also increases. Hence trips are directly proportional to revenue. Good cabs should focus on increasing trips by acquiring new customers or by encouraging more passengers to repeat trips. 
## Repeat Customer Report

![image alt](https://github.com/SUNNY-GAWANDE/Operational-Analytics-on-Goodcabs/blob/e794faf3e2efc06e27bd229b5e8d4d0683bd9d80/Repeat_2.png)

### KPI Performance:
The revenue generated by repeat passengers is 55M with 61K repeat passengers across 249K repeat trips. This dashboard view also shows important KPIs such as Repeat passenger rate and Repeat Trip Ratio with 25.7% and 71% respectively for the entire duration of six months. 
### Repeat Rate by City & Trip Count:
The percentage of Repeat passengers for 2-Trips is 30% which is the highest among all trips. As the number of trips increases its percentage decreases. This indicates good cabs pivot their focus on shorter trips to increase revenue. 
Among cities, Jaipur outperformed all other cities in terms of  Repeat passengers for 2 trips. Here also a general trend follows that with more trips the repeat rate is less favorable. However, cities like Lucknow and Surat show a different trend . It shows Repeat passengers rates were highest for 5-6 trips.
### RPR by Month: 
RPR for the month of January is 19% which is lowest for the period of 6 months and then it increased marginally to 21% for February month. RPR increased gradually for the following month of March and April by 26% and 29% respectively. It has achieved the highest growth in the month of May to 33% and decreased by approximately 3% in the month of May. 
In January revenue from repeating passengers was 7 Million and it increased to next two months with 8M and 9M for February and March respectively. Revenue was flat in April with 9M and it generated maximum revenue of 11M in May. Revenue decreased by 3M in the month of June.
## Trips Report

![image alt](https://github.com/SUNNY-GAWANDE/Operational-Analytics-on-Goodcabs/blob/6c7d841131f7cc2abd69e0b385c0b2089500db04/trips_3.png)

### Total Trips by Day Type:
Total trips in terms of Weekday for January month started with 40,000 and it has marginally increased in the subsequent months of February, March and April. It peaked at 43000 in May. However, after that it decreased to lowest with 35000 in June.
In January Total trips in terms of Weekend is around 31000 and it has achieved the highest trips in February with 35000 trips. After that it has observed a linearly decreasing trend and hit its lowest trips in June.
### Peak and Low Demand Months by City:
Total trips for Goodcabs is 70000 in January and achieved its maximum trips in the next month i.e February with 75000 trips. Although in the next month trips dropped by 1000 and it dropped further 71000. It has marginally regained the total trips in May with a total 73000 trips. Total trips fell to lowest in June with 63000, a drop of 1000 from the previous month.
In terms of citywise and monthly distribution, for Jaipur, January has 15000 trips and February is the peak month with 16000 trips. After that trips demand decreased drastically. These help to understand the dynamics of the demands especially for a city like Jaipur which is a tourist destination. A similar trend for another tourist friendly city is observed for Lucknow. An interesting trend was observed for cities in the northern region of India(Jaipur, Lucknow & Chandigarh) that peak demand month is February with the first quarter of month showing a good amount of demand. This may be due to the winter season with pleasant atmosphere and tourist friendly places in these parts. 
For the rest of the cities which are in the southern and western part of India, the peak demand months are April and May as there are summer holidays. 
## Actual V/s Target Report

![image alt](https://github.com/SUNNY-GAWANDE/Operational-Analytics-on-Goodcabs/blob/295bcd4b727c81e96568753359bc5637f8765c4d/target_4.png)

### KPI Performance:
With targeted trips of 429K over a course of six months, it has achieved 426K total trips and achieved 99% of the target. In terms of a new passenger target of 185K in a period of six months, 177K new passengers were acquired by Good Cabs and  achieved 96% of the new passenger target. 
### City wise Target Analysis:
Cities such as Chandigadh, Coimbatore, Jaipur, Kochi, Mysore and Vishakhapatam have achieved the target. With a total passenger of 16k against a target of 13K Mysore achieved more than 20% of target. Rest cities have not achieved the target with only 32K total trips Vadodara is the least performing city in terms of target of 85%. 
### Month on Month Target Analysis: 
In terms of acquiring a new passenger target cities like Coimbatore, Surat, Indore, Lucknow & Vadodara successfully achieved their target with coimbatore leading with 14% more than target. At other end of spectrum cities like Jaipur, Chandigadh, Vishakhapatam, Mysore & Kochi underachieved their respective target with Jaipur only met with 85% of target.
### Rating Target Analysis:
Maysore, Jaipur & Kochi were the cities that outperformed their target rating with 9 ratings from all these cities.  Chandigarh also did well by achieving the target with 8 ratings. Rest of the cities were not able to achieve its target, Vadodara and Lucknow are the bottom 2 cities with ratings of 6 each. 

## Recommendations:
### Focus on High-Growth Cities:
 Prioritize efforts in cities with high growth potential, such as Jaipur and Kochi, by implementing targeted marketing campaigns and optimizing service delivery.
### Enhance Customer Retention: 
Implement strategies to incentivize repeat trips, such as loyalty programs, referral bonuses, and personalized offers.
### Improve Service Quality: 
Address the concerns of passengers in cities with lower ratings through driver training programs, improved vehicle maintenance, and enhanced customer support.
### Optimize Operations: 
Analyze seasonal demand patterns to optimize resource allocation, such as driver scheduling and vehicle deployment, to ensure efficient service delivery during peak periods.
### Strengthen Data Analysis:
 Leverage data analytics to identify key drivers of customer behavior, predict future demand, and refine marketing strategies for targeted customer acquisition.
