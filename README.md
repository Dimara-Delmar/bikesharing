# Citibike Analysis

## Link to Tableau Dashboard
https://public.tableau.com/app/profile/dbo6844/viz/Module15Challenge_16746246285340/Story1?publish=yes

## Overview of the Project

### Purpose
Kate recently went on a successful vacation to New York city and wanted to replicate their bike-sharing system in her hometown of Des Moines. Investors would be interested in the project if we can gather evidence of it being a fruitful investment. To see how the bike sharing program might work in a different city, we are given the task of analyzing the bike sharing data of New York city and seeing how they make the program work for them. 

Using Tableau public and the New York City Bike-sharing data gathered in August 2019, we will be creating numerous different visualizations to illustrate the potential of replicating a similar program in the city of Des Moines.

## Resources
- Data Sources: `citidata.csv` and `201908-citibike-tripdata.csv`
- Software: Jupyter Notebook 5.2 and Tableau Public 2022.1

## Results

1) This graph displays the length of time bikes are checked out for all riders. Most bikes are checked out for 5 minutes, and the duration of most trips do not last for more than 1 hour. 

<img width="461" alt="Checkout_Times_for_Users" src="https://user-images.githubusercontent.com/108738297/214752592-b6beb591-2e7d-45b6-8373-8f0da9fa8ef5.PNG">

2) This graph uses the same data as the previous graph, with the addition of graphing the duration of checkout time based on user's gender. The data shows that male users use the bikes the most, with female users being the second most frequent users, and unknown genders being the third. 

<img width="459" alt="Checkout_Times_by_Gender" src="https://user-images.githubusercontent.com/108738297/214752613-bd96084f-7b4c-4491-bd97-48a789928056.PNG">

3) The heat map below shows the number of trips taken based on the hour of the day (12am - 11pm) and the day of the week (Sun-Sat). The data shows that bikes are being used most frequently around 5-6pm, most likely when people are communing from work.

<img width="372" alt="Trips_by_Weekday_per_Hour" src="https://user-images.githubusercontent.com/108738297/214752646-20ecfb19-9ef6-4c70-a5e2-94fc349430d0.PNG">

4) This heatmap uses the same data as the previous map, with the addition of filtering the data by gender. We can again see that Male users are the most frequent bike users of all three options, using the bikes around 7am in the morning, and 5-6pm in the afternoon. 

<img width="759" alt="Trips_by_Gender" src="https://user-images.githubusercontent.com/108738297/214752668-9a9a29d0-2dde-44a2-8f1a-92b2f6ad4e58.PNG">

5) This third heatmap shows the number of bike trips taken each day of the week, based on the user's gender, and by each Usertype (customer or subscriber). The most frequent users are Male subscribers renting the bikes during the work week (Mon-Fri), specifically on Thursdays. 

<img width="387" alt="User_Trips_by_Weekday" src="https://user-images.githubusercontent.com/108738297/214752688-02680b00-c05e-4b76-a533-44de1e7a2352.PNG">

6) This pie chart is breaks down the amount of bike riders based on their gender: Male, Female, or Unknown. 
    - Unknown users only make up 9% of the chart with 225,521 users. 
    - Female users make up 25% of the chart with 588,431 user.
    - Male users are the largest population of users, taking up 65% of the chart with 1,530,272 users.

<img width="165" alt="Gender_Breakdown" src="https://user-images.githubusercontent.com/108738297/214752706-694a3e63-1eb0-4e78-ae3c-e9290b21d9e3.PNG">

7) This pie chart demonstrates the amount of bike users that are regular Customers, or Subscribers. 
    - There are 443,865 Customers (18%).
    - 1,900,359 are Subscribers (81%). 

<img width="160" alt="Customers" src="https://user-images.githubusercontent.com/108738297/214752724-6491223b-4031-4068-bf33-caee5b4d603b.PNG">

## Summary

According to the data provided in this analysis, The most frequent users of the bike sharing program in New York city were Male users who were subscribed to the program. They would frequent these rides from 7am and 5-6pm, using them most frequently during weekdays (Mon-Fri). It is very possible that these users were renting bikes to commute to and from work, and most of them only needed to rent the bikes out for rides that lasted upwards of 5 mins to an hour. 

### Extra Visualizations

For future analysis, it may be beneficial to create new visualizations for a deeper understanding of the data. 

1) A graph depicting the correlation between users using the bikes for work communion, versus users using the bikes for nonwork/tourist communion may be beneficial in learning how frequently the bike-sharing program is being used by people needing to travel to work or for tourism. 

2) A graph that shows the number of bikes being rented out throughout the different months of the year, so that we can see if there’s a seasonal trend between bike rentals and the months they are being used. 
