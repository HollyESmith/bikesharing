# bikesharing

## Overview

### Background & Purpose

A pair of individuals are interested in starting a bike share business in Des Moines, Iowa. They have a potential investor who is interested, and my assignment is to analyze existing New York City bike sharing data from August 2019 that might help predict whether the bike-share company idea could work in Des Moines. Once the analysis is complete, I am to transform that analysis into data visualization using Tableau for presentation to potential investors. 

Prior to beginning this project I had to convert the "tripdurtion" datatype to perform the analysis. My working dataframe looked like this after the conversion:

![dataframe](https://user-images.githubusercontent.com/97558998/170529652-bde8b2a9-bf75-40cb-a376-96e42f4779e3.png)

## Results

**August Peak Hours**

First, I analyzed peak hours of usage. This bar chart indicates that peak hours are between 5:00 PM - 7:00 PM:

![PeakHours](https://user-images.githubusercontent.com/97558998/170123913-1e9c7e38-d2f1-4dd6-b7ba-c9cc37b685be.png)

In addition, the bar chart shows that the hours between 1:00 AM - 5:00 AM have the lowest usage, which is an ideal time for maintenance.

![MaintenanceHours](https://user-images.githubusercontent.com/97558998/170124263-cc8be0d3-9491-43bb-870a-16d4e6f43f63.png)

**Top Starting Locations**

I then looked at top starting locations. This scatter plot indicates that the center of the business district may be a good place for advertising to prospective bikesharers.

![TopStartingLocations](https://user-images.githubusercontent.com/97558998/170124556-31a8a733-267e-4649-825b-d55601b27606.png)

**Checkout Times for Users**

This line graph indicates that the duration of bike rides is relatively short:

![CheckoutTime](https://user-images.githubusercontent.com/97558998/170124785-115314d9-0bde-4b97-97e0-25676f8b4d84.png)

**Checkout Times by Gender**

This line graph shows a huge difference between male (approximately 108,000) and female (approximately 34,000) users.

![CheckoutTimesGender](https://user-images.githubusercontent.com/97558998/170124919-f53ce9a5-7b85-49b7-b33c-fb8023916a89.png)

**Trips by Workday**

This heatmap shows that Monday, Tuesday, and Thursday afternoons between 5:00 – 7:00 PM are when most bike trips are taken. Thursday has the most utilization during this time period, with 88,887 riders.

![TripsWorkday](https://user-images.githubusercontent.com/97558998/170125370-00ec5869-4c99-4fa2-bd0b-825e459d896f.png)

**Trips by Gender (Weekday per Hour)**

This heatmap reiterates previous data: Monday, Tuesday, and Thursday afternoons between 5:00 – 7:00 PM are when most bike trips are taken; as demonstrated on the Checkout Times by Gender graph, the majority of bikesharers are male.

![TripsWeekdayGenderHour](https://user-images.githubusercontent.com/97558998/170126635-0e20e3e8-5ac3-4df1-8c9f-d2f1913857c5.png)

**User Trips by Gender by Weekday**

In addition to showing previously shown frequency and gender data, this heatmap indicates that the majority of service subscribers are male.

![TripsGenderUserType](https://user-images.githubusercontent.com/97558998/170127606-a22f018b-5eb9-4a5c-8c9c-d71d67408820.png)

## Summary

Based on this analysis, the investors can conclude that this is a promising business opportunity. I recommend an advertising campaign aimed at males in the densest business districts. The data also show a good picture of the ebb and flow of bike sharing throughout the day. Ideally the analysis would encompass a longer time period, or at least a selection of months throughout the year, to demonstrate seasonal usage. We don’t have any idea of usage during the colder months, which would be necessary to sustain the business. I would also explore income related data by neighborhood to correlate potential usage by those who have more transportation needs.

Here is my Tableau Public link:

https://public.tableau.com/app/profile/holly.smith5305/viz/BikeSharingChallenge_16534139569340/AugustPeakHours?publish=yes![image]

