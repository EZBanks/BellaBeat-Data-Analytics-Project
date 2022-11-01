# BellaBeat-Data-Analytics-Project

## The company

Urška Sršen and Sando Mur founded Bellabeat, a high-tech company that manufactures health-focused smart products. Sršen used her background as an artist to develop beautifully designed technology that informs and inspires women around the world. Collecting data on activity, sleep, stress, and reproductive health has allowed Bellabeat to empower women with knowledge about their own health and habits. Since it was founded in 2013, Bellabeat has grown rapidly and quickly positioned itself as a tech-driven wellness company for women.

## Stakeholders

•	Urška Sršen: Bellabeat’s cofounder and Chief Creative Officer 

•	Sando Mur: Mathematician and Bellabeat’s cofounder; key member of the Bellabeat executive team 

•	Bellabeat marketing analytics team: A team of data analysts responsible for collecting, analyzing, and reporting data that helps guide Bellabeat’s marketing strategy 


## Executive Summary

The aim of this analysis is to focus on one of Bellabeat’s products and analyze smart device data to gain insight into how consumers are using their smart devices. The insights discovered will then help guide marketing strategy for the company. 
This report covers different phases in my analysis to help answer the business questions raised by the management. These phases include Ask questions, Prepare data, Process data, Analyze data, Share data, and Act.

## Methodology

Before performing the analysis, the data was collected through a public domain, then wrangled to make sure it’s cleaned, reliable and error-free by removing duplicates, finding and filling missing values and normalizing data. After that, I explored and found correlation between variables, proceeded to data visualization to better capture trends and insights and finally made highly recommendations to the executive team.


## Ask phase

The executive team asked to analyze smart device fitness data as they could help unlock new growth opportunities for the company. More specifically, the following questions were raised:

   * What are some trends in smart device usage?
   
   * How could these trends apply to Bellabeat customers?
   
   * How could these trends help influence Bellabeat marketing strategy?

## Prepare phase

The data to explore and analyze was made available through FitBit Fitness Tracker Data: http://www.kaggle.com/arahnic/fitbit which is a Public Domain. I proceeded to the collection and the storage of data by making sure they meet the requirements in terms of integrity, reliability, credibility and security. However, going through my analysis I found that there are thirty-three (33) ID (users) instead of thirty (30) as mentioned in the business task. Therefore my analysis will focus on 33 users. I decided to work with the following four (4) data sets as for me they are the most relevant for this analysis task but also for the BellaBeat product I chose to apply my analysis on that is Bellabeat app: Provides users with health data related to their activity, sleep, stress, menstrual cycle, and mindfulness habits. In addition, this product covers and is related to almost all of the other products of the company. These four data sets are:

   * dailyActivity_merged
   
   * heartrate_seconds_merged
   
   * sleepDay_merged
   
   * weightLogInfo_merged

For example, dailyActivity_merged contains other data sets such as dailyCalories_merged and dailySteps_merged which in turn are aggregates of smaller data sets including hourlyCalories_merged, hourlySteps_merged, etc.

Let’s import the data sets

![Screenshot 2022-11-01 at 17-21-41 BellaBeat Data Analytics Project](https://user-images.githubusercontent.com/113363487/199297922-64cdc060-cf77-482a-bb89-3e50798866a4.png)


## Process phase

Before analyzing data, let’s load a number of packages.

