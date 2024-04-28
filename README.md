# Bellabeat-Case-Study-Excel

## Introduction
Bellabeat has rapidly grown into a tech-driven wellness company for women, establishing itself since 2013. The company offers five focus products: the Bellabeat app, Leaf, Time, Spring, and Bellabeat membership. While successful as a small company, Bellabeat sees potential for expansion in the global smart device market. The task at hand is to analyze smart device data. These insights will inform the company's marketing strategy moving forward.

## Ask
**Business Task :** Analyze FitBit fitness tracker data to understand consumer behavior and identify trends for Bellabeat marketing strategy.


## Prepare
**Data Source Information:**

The data used for analysis is publicly available on [Kaggle](https://www.kaggle.com/datasets/arashnic/fitbit) and is sourced from the FitBit Fitness Tracker Data. It consists of 18 CSV files.
A total of 30 FitBit users provided consent for the submission of their personal tracker data.
The collected data includes information on physical activity recorded in minutes, heart rate, sleep monitoring, daily activity, and steps.

**Evaluation of Data Source:**

**Reliability:** The reliability of the data is rated as low due to the small sample size of only 30 respondents.

**Originality:** The data is sourced from a third-party provider (Amazon Mechanical Turk), resulting in a low originality rating.

**Comprehensiveness:** The data provides minute-level output for physical activity, heart rate, and sleep monitoring. However, the sample size is small, and data is mostly recorded during certain days of the week, leading to a medium comprehensiveness rating.

**Currency:** The data is 8 years old, making it less relevant in the current context.

**Citation:** As the data is collected from a third-party source, the citation is considered low, and the origin of the data is unknown.

**Data Selection:**
For analysis, the dailyActivity_merged.csv file has been selected and copied for further examination.


## Process

Tools i used for data exploration and cleaning: Excel

**Data exploration and cleaning:**

1. Check table columns and their data type.
2. After creating a table called 'Fitness' for the entire dataset, check the number of null values for each column in the data.
3. Count the number of unique IDs to confirm whether the data contains the 30 IDs.
4. Convert format of 'ActivityDate' col from mm-dd-yyyy to yyyy-mm-dd.
5. Create new column 'DayOfTheWeek' for further analysis.
6. Create new column 'TotalMinutes' being the sum of VeryActiveMinutes, FairlyActiveMinutes, LightlyActiveMinutes and SedentaryMinutes.
7. Create new column 'TotalHours' by converting new column 'TotalMinutes' to number of hours.


## Analyze and Share
Let's summray the data using pivot table.

![image](https://github.com/yasmena20/Bellabeat-Case-Study-Excel/assets/24322947/82b06874-c02e-454a-b888-6df7c40d31c9)

1. On average, users logged 7,637 steps, falling short of the recommended 10,000 steps per day for optimal health and fitness improvement (Source: CDC).
2. Sedentary users comprise the majority, logging an average of 991 minutes or 20 hours per day, making up 81% of total average minutes.
3. The average calories burned is 2,303, equivalent to approximately 0.6 pounds. However, this may vary depending on individual factors such as age, weight, daily tasks, exercise, hormones, and daily calorie intake (Source: Health Line).
4. Users spent more time, took more steps, and burned more calories on Tuesday compared to other days of the week.<br/><br/>


![image](https://github.com/yasmena20/Bellabeat-Case-Study-Excel/assets/24322947/25a0279b-24c8-4d50-a3c4-b01cb3d57b5f)

Weekly Usage Trends:
The frequency of app usage drops notably on Friday and continues to be lower over the weekends and Monday.<br/><br/> 


![image](https://github.com/yasmena20/Bellabeat-Case-Study-Excel/assets/24322947/2df27ca9-688a-4e0b-8113-40bff16e1070)

Calories Burned per Step:

The scatter plot illustrates the relationship between calories burned and the number of steps taken.

**Correlation:**
There is a positive correlation between steps taken and calories burned.

**Intensity of Calorie Burn:**
I observed that the intensity of calorie burn increases as users take more steps, particularly within the range of 0 to 15,000 steps. However, the calorie burn rate tends to decrease beyond 15,000 steps.<br/><br/>


![image](https://github.com/yasmena20/Bellabeat-Case-Study-Excel/assets/24322947/f8c4b1eb-5cb3-4bf0-b968-ff0928550881)

Correlation:
There is a weak positive correlation observed, where the increase of hours logged does not necessarily translate to more calories being burned. This is largely due to the average sedentary hours being 16:30 hours.<br/><br/>

![image](https://github.com/yasmena20/Bellabeat-Case-Study-Excel/assets/24322947/59fbc303-1bae-4559-a06a-e0510cfc22a8)

As observed from the pie chart:

Sedentary minutes comprise the largest slice at 81%.

This indicates that users are primarily using the FitBit app to log daily activities such as commuting, inactive movements, or running errands.
Fitness Tracking Usage:
The app is rarely being used to track fitness activities such as running, as evidenced by the minor percentage of fairly active activity (1%) and very active activity (2%).

This is concerning, as the FitBit app was developed to encourage fitness and active lifestyles.


## Act

After analyzing the consumer behavior of the app, here are some recommendations:
1. **Enhance Fitness Tracking Features:**
Introduce new features or improve existing ones to make fitness tracking more appealing and user-friendly, encouraging users to log their workouts and activities more frequently.
2. **Provide Personalized Recommendations:**
Offer personalized fitness plans and recommendations based on users' activity levels, goals, and preferences to keep them engaged and motivated.
3. **Educate Users on Benefits:**
Educate users on the benefits of regular physical activity and the importance of reaching daily step goals, such as improved health, increased energy, and better mood.
4. **Incentivize Active Lifestyles:**
Offer rewards or discounts for reaching certain milestones or consistently meeting activity goals to encourage long-term engagement with the app.
