# Citi Bike Sharing

## Overview
Our inital analysis was to evaluate Citi Bike data from August 2019 for New York City to help predict the success of a similar business model in Des Moines.

One of our key stakeholders requested to see bike trip analysis performed to solidfy the proposal. We then created the visualizations below to analyze the bike trip data.

## Results
We created the following 5 visualizations for our key stakeholder that requested to additional bike trip analysis.

### Checkout Times for Users

![checkout times 2](https://user-images.githubusercontent.com/114427019/217681479-f46456ad-8092-42fe-8e9d-a30fb638b31b.png)

Our inital analyis of the length of time that bikes were checked out for all riders showed that the majority of bike rides were within the 1 hour mark. We then decided to invesitage further which produced the image below.

![Checkout times 1](https://user-images.githubusercontent.com/114427019/217681265-5c311a53-a22a-4332-81ec-a71c84929798.png)

We can see that bike rides that lasted five minutes were the most freqent.

### Checkout Times by Gender

![Checkout Genders 1](https://user-images.githubusercontent.com/114427019/217682250-a2a6cd1c-49ed-41ab-9f7d-e3c67d5721c9.png)

In further breaking down the data from "Checkout Times for Users" by adding in a Gender filter, we can see that the Males are buy and large the main contributers to the peak ride time of five minutes.

![Checkout Genders 2](https://user-images.githubusercontent.com/114427019/217682438-734bc317-3532-4a41-89bf-a230aded89e9.png)

When we filer the data even further to only look at the first hour, this is further confirmed that Males are mainly riding the Citibikes for five minutes or so.

### Trips by Weekday for Each Hour

![Trip Weekday](https://user-images.githubusercontent.com/114427019/217682637-a6eeec1b-055c-4270-9a0f-4c9647bb07a8.png)

Based on our analysis, it's clear to see that during the weekday's the most peak times for Citibike usage is during rush hour in the morning and in the evening.

### Trips by Gender (Weekday per Hour)

![Trip Gender](https://user-images.githubusercontent.com/114427019/217682779-54a8fee0-e3b4-439c-8cef-184efae5347a.png)

Based on further analysis, we can conclude that Males are the ones who are mainly using Citibikes during peak hours.

### User Trips by Gender by Weekday

![User Type](https://user-images.githubusercontent.com/114427019/217682101-3ca68dc2-f8e9-4607-a094-94a8b3d0303b.png)

In breaking down the previous visualization even further, we can clearly see that Male Subscribers are the vast majority of people using Citibikes.

## Summary
We complied our visualizationtions in the the following Tableau Story:
[link to dashboard](https://public.tableau.com/app/profile/lily.rackley/viz/Challenge_16758992599580/Challenge)

In summary, it appears that Males are the most frequent users of Citibikes with their trips typically being short 5 min rides. In addition, Males generally are the ones to have subscriptions to Citibikes.

In order to confirm that Male subscribers are the ones who are the primary group of users who are taking the short trips, we recommend an additional chart be created where the chart "Checkout times by Gender" is refactored to include a filter of Subscribers vs. Users by using "Usertype".

In addition, we also recommend creating a map visualization of the most popular stations Male Subscribers are picking up Citibikes are loacted. This way Citibike can anticipate the demand and have more bikes in the more popular startign stations.
