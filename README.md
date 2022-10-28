# Google Data Analytics Bellabeat Case Study

<h2>Scenario</h2>

Bellabeat is a high-tech manufacturer of health-focused products for women. Collecting data on activity, sleep, stress, and reproductive health has allowed Bellabeat to empower women with knowledge about their own health and habits. Since it was founded in 2013, Bellabeat has grown rapidly and quickly positioned itself as a tech-driven wellness company for women.

As a junior data analyst working on the marketing analyst team at Bellabeat, I have been asked to focus on one of Bellabeat’s products and analyze smart device data to gain insight into how consumers are using their smart devices.

<h2>Business question:</h2>

How consumers are using their smart devices.

In order to answer the business question, the six phases of the data analysis process will be followed:

Ask, Prepare, Process, Analyze, Share and Act.

<h3>1.Ask</h3>

First step is to identify the business task. The task is to gain insight from one Bellabeat product into how customers use non-Bellabeat smart devices. Questions to be answered:

What are some trends in smart device usage?
How could these trends apply to Bellabeat customers?
How could these trends help influence Bellabeat marketing strategy?

The stakeholders are:

○ Urška Sršen: Bellabeat’s cofounder and Chief Creative Officer

○ Sando Mur: Mathematician and Bellabeat’s cofounder; key member of the Bellabeat executive team

○ Bellabeat marketing analytics team: A team of data analysts responsible for collecting, analyzing, and reporting data that helps guide Bellabeat’s marketing strategy.

<h3>2.Prepare</h3>

FitBit Fitness Tracker Data was downloaded from Kaggle given by Google Data Analytics Course.

Source: <a href="https://www.kaggle.com/datasets/arashnic/fitbit">FitBit Fitness Tracker Data</a>  under the <a href="https://creativecommons.org/publicdomain/zero/1.0/">licence</a>

Since the data given is taken from the website https://www.fitbit.com/global/eu/home we have the following limitations:

○ Although Bellabeat products are made for women, given the fact that the data is from FitBit site, the gender is unknown.

○ The site suggests to remove the device for one hour so to give the wrist a rest. That way we have missing data.

○ Those made of leather, metal or woven are suggested not to be worn during high-intensity workouts. (Data limitation as well).

○ There might be problems with sync in case of bad network connection.

Despite the limitations data process is going to be continued with data given.

Files are in .csv format.

Software: R Studio Desktop

<h3>3.Process</h3> View <a href="https://github.com/Dimitra-Nikoloutsou/Google_Data_Analytics_Bellabeat_Case_Study/blob/main/R%20file">R File</a>  

<h3>4.Analyse</h3> View <a href="https://github.com/Dimitra-Nikoloutsou/Google_Data_Analytics_Bellabeat_Case_Study/blob/main/R%20file">R File</a>  

<h3>5.Share</h3>

![download](https://user-images.githubusercontent.com/114480002/198731400-45f02361-92a9-461b-8232-b3f4e8a9e390.png)
![download (1)](https://user-images.githubusercontent.com/114480002/198731432-97e7802a-dc99-4aa6-a0b9-228b8b9d0bcc.png)
![download (2)](https://user-images.githubusercontent.com/114480002/198731455-28f16885-64d4-49b4-880d-6bcfbee53b0a.png)

<h1>INSIGHTS</h1>

Average steps, 8319, is considered low active. According to the CDC, most adults should aim for 10,000 steps per day for general health and especially if the target is fitness or weight loss.

Average sedentary minutes, 955.8 or 15.9 hours, is too high compared to the active minutes and that is something that should change for health promotion.

Light Active Distance has the highest average which means that the users are not very active.

However the average MET is 14.69 which corresponds to vigorous activities that aren't probably practiced often.

From the first scatter plot it is obvious that the more steps the more calories are burned.

From the Average Total Intensity VS Time histogram we can observe that the most popular hours are between 17:00 and 19:00. The users choose this time period for activities because it is after working hours.

Most of the users choose to practice vigorous activities that require more energy for the muscles. However, there is a negative relationship between the mean seconds and the METs. Knowing the MET value of an activity can also be helpful in calculating how many calories are burned during exercise. The formula requires the weight too but as the data is missing and we have weight data for only 8 users, conclusions and recommendations won't take place for this data.

<b>Published in <a href="https://www.kaggle.com/code/dimitranikoloutsou/bellabeat-case-study">Kaggle</a>  
