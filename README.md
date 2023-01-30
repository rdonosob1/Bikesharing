# Bike-sharing
Using Tableau, data visualization software to present a business proposal about a bike-sharing company. 

## Project Overview
First of all, this project will consist in importing, styling, and portraying data accurately from a New York Citi Bike dataset. Consequently, worksheets, dashboards and stories will be created in order to visualize that data. However, this is only the starting point of the project. After that, more work has to be done to convince investors that a bike-sharing program in Des Moines is a solid business proposal. Therefore, as part of this analysis we will illustrate the following: 

* The length of time that bikes are checked out for all riders and genders
* The number of bike trips for all riders and genders for each hour of each day of the week
* Show the number of bike trips for each type of user and gender for each day of the week.

Finally, these visualizations will be added as a tableau story for a final presentation and analysis to pitch to investors.

## Results
### Deliverable 1
A previous work needed to be performed before the analysis. So, I needed to use Python and Pandas functions to convert the "tripduration" column from an integer to a datetime datatype to get the time in hours, minutes, and seconds. After converting the "tripduration" column to a datetime datatype, I exported the DataFrame as a CSV file. This will be my input for the analysis of this project in both Deliverable 2 and 3. 

The following image illustrates the converted values in the "tripduration" column to datetime datatype.

![image](https://github.com/rdonosob1/Bikesharing/blob/main/Resources/DataFrame%20-%20Deliverable%201.png)

### Deliverable 2
This consisted in creating visualizations that show the following:

* How long bikes are checked out for all riders and genders.
* How many trips are taken by the hour for each day of the week, for all riders and genders.
* A breakdown of what days of the week a user might be more likely to check out a bike, by type of user and gender.

The results are shown below
#### Types of users: Short-Term customers vs Annual subscribers - Visualization
![image](https://github.com/rdonosob1/Bikesharing/blob/main/Resources/Deliverable%202/Customer_break_down.png

#### Gender breakdown Find the Number of Rides by Gender - Visualization
![image](https://github.com/rdonosob1/Bikesharing/blob/main/Resources/Deliverable%202/gender_break_down.png)

#### Checkout Times for Users - Visualization
![image](https://github.com/rdonosob1/Bikesharing/blob/main/Resources/Deliverable%202/checkout_times_for_all_users.png)

#### Checkout Times by Gender - Visualization
![image](https://github.com/rdonosob1/Bikesharing/blob/main/Resources/Deliverable%202/checkout_times_by_gender.png)

#### Trips by Weekday for Each Hour - Visualization
![image] (https://github.com/rdonosob1/Bikesharing/blob/main/Resources/Deliverable%202/heatmap_trips_per_hour.png)

#### Trips by Gender (Weekday per Hour) - Visualization
![image](https://github.com/rdonosob1/Bikesharing/blob/main/Resources/Deliverable%202/heatmap_time_by_gender_weekday-hour.png)

#### Trips by Gender and by usertype by Weekday - Visualization
![image](https://github.com/rdonosob1/Bikesharing/blob/main/Resources/Deliverable%202/heatmap_user_gender_weekday.png)

## Summary
Below you will find a summary of the results found on this analysis.
The types of users’ pie chart showed that 1,900,359 of the total users (2,344,224) are subscribers. It represents 81% of the total # of users. In addition to that, the investors will be well aware that these subscriptions can be translated as fixed revenue and therefore it will help to their future forecasting for expansion, as well as other decisions such acquiring more bikes, maintenance programs, etc. 
In addition to that, it is clear that at least 65% of the users are men. It may be useful for future publicity as well as other campaigns needed or focusing more in targeting the women market. 

Other important factor that we have discovered after the analysis is that the peak hours for that business differ from weekdays than weekends. It is clear that during Monday - Friday, people tend to ride the bikes during two different times. During the afternoon-evening, from 5pm to 7pm is where we see a trend of use. However, in the morning a similar scenario happens between 7am to 9am. On the other hand, during the weekend we see more demand between 10am to 7pm. Knowing this information will help to determine some actions such as: 
 * The days and times the service will need to have more available bikes
 * When it will be more appropriate to perform maintenance activities

Finally, the last visualization (Trips by Gender and by usertype by Weekday) shows that the service is more demanded by males and also that Thursdays and Fridays is when the service is more demanded. 

### Recommendations:
For future analysis it'd be important to perform the following additional visualizations:
  * A breakdown of customers by date of birth (age) to know better the target market.
  * A breakdown by bikeid to show the bikes that are used the most.

#### Tableau URL:
[link to dashboard](https://public.tableau.com/views/Bike-SharingDesMoines/Story1?:language=es-ES&publish=yes&:display_count=n&:origin=viz_share_link)

