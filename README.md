# **BellaBeat Case Study**       ![image](https://user-images.githubusercontent.com/110743067/183266244-967f3e0a-2450-42be-8400-998e2e442c13.png)

# Ask
## What is the Goal?

Find common usage trends in non-BellaBeat smart devices and identify what insight can we use to market one of our current products.


## Questions to answer:
* What are some trends in the smart devise usage?
* How could these trends apply to Bellabeat customers?
* How could these trends help influence Bellabeat marketing strategy?

# Prepare
## Overview of Assets
* Personal fitness tracking data from 30 consenting Fitbit users.
* Datasets contains
	* FitBit Fitness Tracker Data (CC0: Public Domain, dataset made available through Mobius) 
	* 31 days of data (4/12/2016 – 05/10/2016)
	* 18 .csv files with data on:
		* Activity
		* Calories
		* Steps
		* Heart Rate
		* Sleep
		* Weight Loss
* We will be utilizing 3 of the 18 datasets, as they encompass the same data at the others.
	* Activity
	* Sleep
	* Weight Loss
* I will be using the following programs to clean, process and analyze the data:
	* Excel
	* SQL
	* Tableau

# Process
## Data Cleaning
* Edited **Id** fields to read **User 1, User 2**, etc., for easier identification.
* Seperated the data and time from the Date field for a 3 files. 
* Removed duplicate on sleep data.

## Limitations
* **Sample Size:** A sample size of 30 is too small to gain unbiased analysis on.
* **Usage Consistency:** Not all users used all functions (heart rate, weight lose, etc), causing the sample data for those inputs to be lower than 30 users in some cases. There is also only 31 days of data collected.
* **Credibility:** This data is secondary, and with no communication from the original owner, we cannot confirm the data credibility.
* **Data Integrity:** Although the sample size was stated as 30 users, there are more than 30 unique IDs in some datasets. There is also not clear perimeters on the data collected, such as what constitutes light vs fair activity.

**These limitations make the data insufficient to answer the questions we have, especially paired with no stakeholders available. In a real life scenario I would not confidently advise any marketing campaign to be built around the insight from this data alone.**

# Analysis
**What are some trends in smart device usage?**

Trends in:
* Daily Activity
* Steps
* Sleep and weight recorded

## Daily Activity Recorded
An average of 78% of the daily hours were recorded

Types of Activity Recorded:
* Sedentary
* Lightly Active
* Fairly Active
* Very Active 

![Hoursrecorded](https://user-images.githubusercontent.com/110743067/183265112-23e718d1-a2fe-42cc-b4f7-6d0b3c2fdda7.png)

## Daily Activity
Sedentary hours accounted for 81% of total active hours recorded.

![image](https://user-images.githubusercontent.com/110743067/183265525-69d85e4e-f5d4-4a66-aaa1-0e20f57c5af6.png)

## Daily Activity & Step Relation
The higher the activity the high the step count. The total active minutes is not including any sedentary time.

![image](https://user-images.githubusercontent.com/110743067/183265632-5fa92b5e-1e6e-43ef-8f82-700029cd711e.png)

## Weight Recorded
Only 8 users recorded their weight during the 31 days, with only 2 user recording for more than 5 days.

![image](https://user-images.githubusercontent.com/110743067/183265651-7004cfe0-d26c-49f6-828d-40c7f8d8fe75.png)

## Sleep Recorded
32 users recorded their sleep for an average of 17 days, during the 31 days of data.

![image](https://user-images.githubusercontent.com/110743067/183265676-70056104-ad9d-4526-9b4c-0cc377170cd5.png)

# Share
## What Have We Learned From the Data?
* Users wear their Fitbit for an average of 78% of the day.
* Users are generally only lightly active.
* Users do not seem to be interacting with or manually logging information for their Fitbit, given the data. 

# Act
## How could these trends apply to Bellabeat customers?
* Based of of the limited data that we have, BellaBeats Time watch can be used to track this same data.
* Bellabeat should incorporate more automated functionality to their watch.
* Work towards simple, non invasive ways to incorporate interaction between the user and the device.

## How could these trends help influence Bellabeat marketing strategy?
* I would propose a marketing campaign around the automated features that the Time watch has to offer.
* If there are currently simple or fun interactive aspects of the watch, focus on those. Users seem to want to get more information out of the device, not spend time manually adding information.


