# Google-Data-Analytics-Capstone-Project
Google Data Analytics Professional Certificate Capstone Project


## Table of Contents

1. [Introduction](README.md#introduction)
2. [Business Task](README.md#business-task)
3. [Data](README.md#data)
4. [Processing, Cleaning, Analysis and Viz Code: R Studio](https://github.com/ckkummer/Google-Data-Analytics-Capstone-Project/blob/c1a1b58b6603b111a8dbcdfcfce1f597138ec1cb/Case%20Study%20R.Rmd)
5. [R Studio Viz](https://github.com/ckkummer/Google-Data-Analytics-Capstone-Project/blob/8ca062912be0fcc53cbddafca211da5549079588/Viz%20in%20R%20Studio)
6. [Preparing and Cleaning For Tableau Code: R Studio](https://github.com/ckkummer/Google-Data-Analytics-Capstone-Project/blob/c1a1b58b6603b111a8dbcdfcfce1f597138ec1cb/Case%20Study%20R.Rmd)
7. [Tableau Dashboard](https://public.tableau.com/views/GoogleDataAnalyticsCapstoneDashboard/Dashboard62?:language=en-US&:display_count=n&:origin=viz_share_link)
8. [Analysis and Viz](README.md#Analysis-and-Viz)
9. [Conclusions and Recommendations](README.md#Conclusions-and-Recommendations)

## Introduction

**Google Data Analytics Professional Certificate Course 8/8: Google Data Analytics Professional Certificate Capstone Project**

This project requires me to act as a fictional  junior analyst working on the marketing analyst team for the fictional company, Cyclistic- a bike-share company based in Chicago. Cyclistic is a program that features more than 5,800 bicycles, 600 docking stations, and offers reclining bikes, hand tricycles, and cargo bikes.

Cyclistic appeals to a broad range of customers by offering flexible pricing plans: single-ride passes, full-day passes, and annual memberships. Customers who purchase single-ride or full-day passes are referred to as casual riders. Customers who purchase annual memberships are Cyclistic members.

Cyclistic’s director of marketing is interested in designing marketing strategies aimed at converting casual riders into annual members. 

## Business Task

In order to design marketing strategies aimed at converting casual riders into annual riders, I have been tasked with answering the following:

“How do annual members and casual riders use Cyclistic bikes differently?”

> **Objective** :The goal is to discern patterns within the historical ride-trip data of Cyclistic, shedding light on the distinct ways Cyclistic members and casual riders engage with the service. This involves the thorough cleaning, analysis, and visualization of the data to uncover meaningful insights.



## Data

* **Data source** :
 The data has been made available by Motivate International Inc.
> **[Cyclistic’s historical trip data]**
> https://divvy-tripdata.s3.amazonaws.com/202301-divvy-tripdata.zip
> https://divvy>tripdata.s3.amazonaws.com/202302-divvy-tripdata.zip
> https://divvy-tripdata.s3.amazonaws.com/202303-divvy-tripdata.zip
> https://divvy-tripdata.s3.amazonaws.com/202304-divvy-tripdata.zip
> https://divvy-tripdata.s3.amazonaws.com/202305-divvy-tripdata.zip
> https://divvy-tripdata.s3.amazonaws.com/202306-divvy-tripdata.zip
> https://divvy-tripdata.s3.amazonaws.com/202307-divvy-tripdata.zip
> https://divvy-tripdata.s3.amazonaws.com/202308-divvy-tripdata.zip
> https://divvy-tripdata.s3.amazonaws.com/202309-divvy-tripdata.zip
> https://divvy-tripdata.s3.amazonaws.com/202310-divvy-tripdata.zip
> https://divvy-tripdata.s3.amazonaws.com/202311-divvy-tripdata.zip
> https://divvy-tripdata.s3.amazonaws.com/202312-divvy-tripdata.zip


* **Date Range** : January 2023 - December 2023
* **Data Attributes** : ride_id,	rideable_type,	started_at,	ended_at,	start_station_name,	start_station_id,	end_station_name,	end_station_id,	start_lat,	start_lng,	end_lat,	end_lng,	member_casual


## Analysis and Viz

The final dataset containing trip data of roughly 3.4 million ride records was analyzed. 
Visualizations were developed in Google Data Studio to observe differential trends between the usage by casual riders and annual members.  


### Compostion of Riders
![Sheet 7 (2)](https://github.com/ckkummer/Google-Data-Analytics-Capstone-Project/assets/114955006/b0bc205a-80ff-4319-952c-4288844d5709)
#### **Insights**
* 64.62% of total rides were taken by members.
* 35.38% of total rides were taken by casual riders.
* Long term focus: membership retention rates and maximizing the number fo members as they are responsible for a majority of the company's business.


### Weekly distribution of number of rides
![# Rider _ Wk day bar](https://github.com/ckkummer/Google-Data-Analytics-Capstone-Project/assets/114955006/703a323d-b0df-4e6a-baae-d62e56403851)
![# Rider _ Wk day bar (6)](https://github.com/ckkummer/Google-Data-Analytics-Capstone-Project/assets/114955006/7f43453b-7f3f-47da-b84d-e6192cdde90d)
#### **Insights**
* Members tend to utlizie bikes during the weekdays Monday - Friday; rider count peaking Tuesday - Thursday
* Roughly 50% of Casual Riders ride on the weekend, Firday - Sunday
* These trends indicate that members are likely utiliing Cyclisitc bikes for means of commuting
* Casual riders are likely utilizing Cyclistic bikes leisurely
  

### Weekly distribution of average ride duration
![# Rider _ Wk day bar (7)](https://github.com/ckkummer/Google-Data-Analytics-Capstone-Project/assets/114955006/2f596834-35d9-49e8-8164-992cf8b55749)
#### **Insights**
* Casual riders typically ride approximately 2 times as long as members ride
* Both causal and member riders engagge in longer rides on the weekend


### Hourly distribution of number of rides
![Hourly](https://github.com/ckkummer/Google-Data-Analytics-Capstone-Project/assets/114955006/1f0fa050-75f8-4467-84de-7c5be3bb08d6)
#### **Insights**
* Members tend to utilize bikes between the hours 6-8 and 16-18
* Casual rider count increased notably throughout the day, then showed a steady decline around hour 18.
* Members may predominantly use bikes for commuting to and from work on weekdays
* Casul riders utilize bikes frequently throughout the day



### Monthly distribution of number of rides 
![Monthly](https://github.com/ckkummer/Google-Data-Analytics-Capstone-Project/assets/114955006/837a2011-6ec9-4da3-b54f-5366d7d49527)
#### **Insights**
* Number of casual riders is approximately normal- showing peak number of riders in July
* Number of member riders is very roughly normal- yet showing peak number of riders in August, followed by July then June
  

## Conclusions and Recommendations
#### **Targeted Marketing:**
* Focus marketing efforts on converting casual riders into members by emphasizing the benefits of annual membership, such as cost savings and convenience for daily commuting.
* Focus membership promotion during peak riding months (Summer)
* Membership retention efforts:
1) free buddy ride 1 time per billing cycle
2) exclusive member events
3) personalized offers
4) introduce loyalty program
   
#### **Promotions:**
* Introduce flash promotions on weekdays and weekends (discunts, BOGO deals...) for casual riders during weekdays to encourage more usage.
* Introduce ride duration packages- longer rides for cheaper
* Introduce discounted memberships for students or for employees at partnered companies
* Hire influencers to promote the company and provide new user awareness / education
* Discounted rides if you referred someone new to the company
