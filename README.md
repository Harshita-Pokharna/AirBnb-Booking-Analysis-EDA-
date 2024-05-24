# CAPSTONE-PROJECT-1--AirBnb-Booking-Analysis
![AirBnb](https://adamhoward56.github.io/Airbnb/airbnb_newyork.jpg)
![image](https://github.com/Harshita-Pokharna/CAPSTONE-PROJECT-1--AirBnb-Booking-Analysis/assets/169404176/5706f80a-e3d7-4c1a-8125-62f0658e8244)

![](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)
# Table of Contents   
- [Abstract](#Abstract)
- [Project Files Description](#Project-Files-Description)
- [Introduction](#Introduction)
- [About the Dataset](#About-the-Dataset)
- [Python Libraries Used](#Python-Libraries-Used)      
- [Project Work Flow](#Project-Work-Flow) 
- [Purpose of the Analysis ](#Purpose-of-the-Analysis)
- [Future Scope](#Future-Scope)
- [Conclusion](Conclusion)

  
![](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

# Abstract 
Airbnb is a global online marketplace for lodging and tourism experiences, it has transformed the way people travel and find accommodations. By providing a platform for individuals to rent out their properties or spare rooms to travelers, Airbnb has created a vast network of lodging options worldwide.This study analyzes the 2019 Airbnb booking data for New York City, focusing on trends and patterns in listings, reviews, prices, and availability. Findings reveal significant spatial variations, with Manhattan having the highest prices and occupancy, and lower demand in Staten Island and the Bronx. It offered offer valuable insights into travel trends, preferences, and market dynamics. These insights are valuable for hosts, policymakers, and researchers in understanding and strategizing within the short-term rental market.The objective of this analysis is to deliver insights to understand guests demands better and thus help hosts and stakeholders to improve their businesses . We have tried to discover the relationships among various attributes such as which roomtype is most preffered,which is the most popular hotspots for travelers in Newyorkcity,Popular hosts, reviews and many such other attributes.

![](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

# Project Files Description
This Project includes 1 colab notebook, 1 ppt pdf

### Executable Files:

[Airbnb Booking Analysis](https://github.com/Harshita-Pokharna/CAPSTONE-PROJECT-1--AirBnb-Booking-Analysis/blob/main/CAPSTONE_PROJECT_No_1_AirBnb_Bookings_Analysis.ipynb)- Includes all codes required for airbnb booking analysis

### Output:
[Google Colab](https://github.com/Harshita-Pokharna/CAPSTONE-PROJECT-1--AirBnb-Booking-Analysis/blob/main/CAPSTONE_PROJECT_No_1_AirBnb_Bookings_Analysis.ipynb) - All the outputs are visible in the provided colab notebook.
  
### Input Files:
Airbnb NYC Data.csv - It contains the basic details of the airbnb booking such as host_name,room_type,neighbourhood_group etc.

### Data Source:
[Dataset] - Dataset taken from Almabetter


![](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

## Introduction
<ul style="list-style-type: circle;">
  <li>Airbnb, Airbnb is actually a short version of the platform’s original name, AirBedandBreakfast.com.
  Founded in 2008 by Brian Chesky, Joe Gebbia, and Nathan Blecharczyk,Airbnb has transformed the way people travel and experience the world. Airbnb began as a simple idea to provide affordable accommodations by connecting travelers with hosts who have extra space to rent. What started as a small startup has now become a global hospitality phenomenon, offering millions of unique accommodations in over 220 countries and regions.</li>
  <li> Airbnb is more than just a booking platform; it's a community-driven marketplace that connects travelers with local hosts who open their homes and share their communities, fostering genuine connections and cultural exchanges.</li>
  <li>With millions of listings, ranging from cozy apartments and rustic cottages to luxurious villas and unique stays, Airbnb caters to every travel style and budget, ensuring personalized and memorable experiences for guests.</li>
  <li>Through Airbnb Experiences, travelers can discover curated activities and adventures led by passionate locals, allowing them to immerse themselves in the culture, cuisine, and lifestyle of their destination.</li>
  <li> By empowering travelers to explore the world with curiosity and connection, Airbnb has democratized travel, turning every trip into an opportunity for adventure, discovery, and meaningful connections with people and places around the globe.</li>
</ul>

![](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

## About the Dataset
<ul style="list-style-type: circle;">
<li>I have used Airbnb bookings 2019 New York City data  .</li>

<li>This dataset contains information about Airbnb bookings in New York City in 2019 that includes information about the hosts, geographical data, reviews and other potential predictors of price.
By analyzing this data,we may be able to understand the trends and patterns of Airbnb use in the NYC.</li>

<li>The Data includes both categorical and numeric values, providing a diverse range of information about the listings.</li>

<li>This Dataset may be useful for analyzing trends and patterns in the Airbnb market in New York and also gain insights into the preferences and behavior of Airbnb users in the area.</li>

<li>Number of observations: 48895</li>

<li>Number of features: 16</li>
</ul>

![](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

## Python Libraries Used
<ul style="list-style-type: circle;">
<li> Numpy - for linear algebra</li>
<li>Pandas - for manipulating and preprocessing the data</li> 
<li>Matplotlib.pyplot - more pretty plots</li>
<li>Seaborn - making pretty plots (uses matplotlib)!</li>
</ul>

![](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

## Project Work Flow
<ul style="list-style-type: circle;">
<li>Importing Libraries</li>

<li>Loading the Dataset</li>

<li>explore Dataset</li>

<li>Data Cleaning and manipulate</li>

<li>Handling Outliers</li>

<li>Data Visualization</li>

![](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

## Purpose of the analysis
<ul style="list-style-type: circle;">
<li>"The purpose of this Airbnb booking analysis is to gain insights into the booking patterns, pricing trends, and customer preferences within the Airbnb ecosystem.
<li>This analysis will inform strategic decisions for hosts, property managers, and stakeholders, enabling them to maximize occupancy rates, increase revenue, and deliver exceptional hospitality services in line with evolving market trends and customer expectations."</li>
<li>This data can be analyzed and used for security, business decisions, understanding of customers and providers (hosts) behavior and performance on the platform, guiding marketing initiatives, implementation of innovative additional services and much more.</li>
</ul>

![](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

## Future Scope

The future scope of an Airbnb booking analysis project is expansive, given the dynamic nature of the short-term rental market and the evolving needs of various stakeholders. Here are several potential areas for further development and research:

Enhanced User Interfaces: Develop more intuitive and user-friendly interfaces for hosts and guests to navigate the platform and utilize analytical tools.
* Guest Preferences: Use machine learning to analyze past booking behavior and preferences to offer personalized recommendations for guests.
* External Data Sources: Incorporate data from external sources such as social media trends, weather patterns, and economic indicators to provide a more holistic view of factors influencing bookings.
* Real-Time Data Analysis: Implement real-time data processing capabilities to provide up-to-the-minute insights and recommendations for hosts and guests.
* Demand Forecasting: Implement more sophisticated machine learning models to predict booking demand based on seasonality, local events, economic conditions, and emerging travel trends.
* Pricing Optimization: Develop dynamic pricing algorithms that consider competition, demand fluctuations, and market trends to help hosts optimize their pricing strategies.
* 
![](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

## Conclusion
The Airbnb booking analysis of NYC's 2019 data reveals crucial insights into the short-term rental market:
* Certain properties emerge as highly popular among guests,as the Hillside Hotel emerges out as the most popular in Newyork.

* The top hosts (top3:Michael, David, and John) in New York exhibit a significant presence in the Airbnb market, with a high number of listings , indicating their strong influence and popularity among guests and also there is a high level of competition among Airbnb hosts, as a small number of hosts dominates a large portion of the market. Hosts should  consider investing in property in areas with relatively fewer listings in order to differentiate themselves from the competition.

* Different neighborhoods in New York offer varying accommodation options, with some neighborhoods being more popular among guests than others.Brooklyn comes in second with significant number of listings and cheaper prices as compared to the Manhattan: With most listings located in Williamsburg and Bedford Stuyvesant two neighborhoods strategically close to Manhattan tourists get the chance to enjoy both boroughs equally while spending less.

* Williamsburg, Bedford-Stuyvesant, Harlem, Bushwick, and the Upper West Side are the top neighborhoods in terms of listing counts, indicating strong demand for Airbnb rentals in these areas.

* The data reveals 3 types of room types available on Airbnb in New York, including entire homes/apartments, private rooms, and shared rooms, catering to different guest preferences, group sizes, and budgets.
  * The majority of listings on Airbnb are for entire homes or apartments and it emerge as the most popular room type, attracting a significant portion of bookings and indicating a preference among guests for privacy, space, and convenience.
  * Private rooms are appealing to those seeking a balance between privacy and affordability and
  * While shared rooms represent a smaller proportion of bookings, they offer budget-friendly options for solo travelers or those seeking a communal living experience, with opportunities for cultural exchange and networking.
*  Prices for Airbnb listings in New York vary significantly depending on factors such as room type, location, and amenities offered.The average price of a listing in New York City is higher in the center of the city (Manhattan) compared to the outer boroughs. This could indicate that investing in property in Manhattan may be more lucrative for Airbnb rentals. But Manhattan and Brooklyn have the largest number of hosts, indicating a high level of competition in these boroughs.

* From our analysis it came out that Reviews also played a crucial role in shaping pricing strategies for different room types and influencing the desirability and competitiveness of neighborhood groups within the Airbnb market. Hosts and property managers can leverage review data to optimize pricing, improve guest satisfaction, and position their listings effectively within the competitive landscape of New York's hospitality industry.

* The data suggests that Airbnb rentals are primarily used for short-term stays, with relatively few listings requiring a minimum stay of 30 nights or more. Hosts may want to consider investing in property that can accommodate shorter stays in order to maximize their occupancy rate.

* The data indicates that the availability of Airbnb rentals varies significantly across neighborhoods and room type, with some neighborhoods having a high concentration of listings and others having relatively few and Shared Room is available for use the most number of the days in the year than any other room type.

* The future scope of the Airbnb booking analysis project is promising, with potential advancements in predictive modeling, data integration, and personalized recommendations.Further research could enhance market and competitor insights, evaluate economic and social impacts, and improve user experience through innovative technologies.


