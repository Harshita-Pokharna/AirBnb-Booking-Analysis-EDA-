# CAPSTONE-PROJECT-1--AirBnb-Booking-Analysis
![AirBnb](https://adamhoward56.github.io/Airbnb/airbnb_newyork.jpg)
![image](https://nebula.wsimg.com/081f48a333f107ad4ce3cb09ca8d0ab6?AccessKeyId=AD279F1A177B2FB2B2B7&disposition=0&alloworigin=1)
![](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)
# Table of Contents   
- [Abstract](#Abstract)
- [Project Files Description](#Project-Files-Description)
- [About the Dataset](#About-the-Dataset)
- [Python Libraries Used](#Python-Libraries-Used)      
- [Project Work Flow](#Project-Work-Flow) 
- [Purpose of the Analysis ](#Purpose-of-the-Analysis)
- [Future Scope](#Future-Scope)
- [Challenges Faced](#Challenges-Faced)
- [Conclusion](#Conclusion)

  
![](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

# Abstract 
Airbnb is a global online marketplace for lodging and tourism experiences, it has transformed the way people travel and find accommodations. By providing a platform for individuals to rent out their properties or spare rooms to travelers, Airbnb has created a vast network of lodging options worldwide.This study analyzes the 2019 Airbnb booking data for New York City, focusing on trends and patterns in listings, reviews, prices, and availability. Findings reveal significant spatial variations, with Manhattan having the highest prices and occupancy, and lower demand in Staten Island and the Bronx. It offered offer valuable insights into travel trends, preferences, and market dynamics. These insights are valuable for hosts, policymakers, and researchers in understanding and strategizing within the short-term rental market.The objective of this analysis is to deliver insights to understand guests demands better and thus help hosts and stakeholders to improve their businesses . We have tried to discover the relationships among various attributes such as which roomtype is most preffered,which is the most popular hotspots for travelers in Newyorkcity,Popular hosts, reviews and many such other attributes.

![](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

# Project Files Description
This Project includes 1 colab notebook.

### Executable Files:

[Airbnb Booking Analysis](https://github.com/Harshita-Pokharna/CAPSTONE-PROJECT-1--AirBnb-Booking-Analysis/blob/main/CAPSTONE_PROJECT_No_1_AirBnb_Bookings_Analysis.ipynb)- Includes all codes required for airbnb booking analysis

### Output:
[Google Colab](https://github.com/Harshita-Pokharna/CAPSTONE-PROJECT-1--AirBnb-Booking-Analysis/blob/main/CAPSTONE_PROJECT_No_1_AirBnb_Bookings_Analysis.ipynb) - All the outputs are visible in the provided colab notebook.
  
### Input Files:
#### Airbnb NYC Data.csv 

### Data Source:
[Dataset] - Dataset taken from Almabetter

![](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

## About the Dataset
<ul style="list-style-type: circle;">
<li>I have used Airbnb bookings 2019 New York City data  .</li>

<li>This dataset contains information about Airbnb bookings in New York City in 2019 that includes information about the basic details of the airbnb booking such as:
 'name',
 'host_id',
 'host_name',
 'neighbourhood_group',
 'neighbourhood',
 'latitude',
 'longitude',
 'room_type',
 'price',
 'minimum_nights',
 'number_of_reviews',
 'last_review',
 'reviews_per_month',
 'calculated_host_listings_count',
 'availability_365'.</li>
  
<li>By analyzing this data,we may be able to understand the trends and patterns of Airbnb use in the NYC.</li>

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

<li>Exploring Dataset</li>

<li>Data Cleaning and Manipulating</li>

<li>Handling Outliers</li>

<li>Data Visualization</li>

<li>Conclusion</li>
</ul>

![](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

## Purpose of the analysis
<ul style="list-style-type: circle;">
<li>The purpose of this Airbnb booking analysis is to gain insights into the booking patterns, pricing trends, and customer preferences within the Airbnb ecosystem.
<li>This analysis will inform strategic decisions for hosts, property managers, and stakeholders, enabling them to maximize occupancy rates, increase revenue, and deliver exceptional hospitality services in line with evolving market trends and customer expectations.</li>
<li>This data can be analyzed and used for security, business decisions, understanding of customers and providers (hosts) behavior and performance on the platform, guiding marketing initiatives, implementation of innovative additional services and much more.</li>
</ul>

![](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

## Future Scope

The future scope of an Airbnb booking analysis project is expansive, given the dynamic nature of the short-term rental market and the evolving needs of various stakeholders. Here are several potential areas for further development and research:

* Enhanced User Interfaces: Develop more intuitive and user-friendly interfaces for hosts and guests to navigate the platform and utilize analytical tools.
* Guest Preferences: Use machine learning to analyze past booking behavior and preferences to offer personalized recommendations for guests.
* External Data Sources: Incorporate data from external sources such as social media trends, weather patterns, and economic indicators to provide a more holistic view of factors influencing bookings.
* Real-Time Data Analysis: Implement real-time data processing capabilities to provide up-to-the-minute insights and recommendations for hosts and guests.
* Demand Forecasting: Implement more sophisticated machine learning models to predict booking demand based on seasonality, local events, economic conditions, and emerging travel trends.
* Pricing Optimization: Develop dynamic pricing algorithms that consider competition, demand fluctuations, and market trends to help hosts optimize their pricing strategies.
  
![](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

## Challenges Faced
* Examining the business KPIs for Airbnb and devising a  solution to the problem.
* Handling the duplicate , Null values  and outliers  in the dataset.
* Designing multiple visualizations to summarize the information in  the dataset and successfully communicate the results and trends to  the reader.

## Conclusion
The Airbnb booking analysis of NYC's 2019 data reveals crucial insights into the short-term rental market:
* Certain properties, like the Hillside Hotel, are highly popular among guests in New York. Top hosts Michael, David, and John dominate the Airbnb market, indicating strong influence and competition. Investing in areas with fewer listings can help hosts stand out.

* Brooklyn offers cheaper options than Manhattan, with most listings in Williamsburg and Bedford-Stuyvesant. Popular neighborhoods for Airbnb rentals include Williamsburg, Bedford-Stuyvesant, Harlem, Bushwick, and the Upper West Side.

* Airbnb offers entire homes/apartments, private rooms, and shared rooms. Entire homes are the most popular, offering privacy and convenience, while private rooms balance privacy and affordability. Shared rooms, although fewer, cater to budget travelers.

* Prices vary by room type, location, and amenities. Listings in Manhattan are pricier, suggesting higher profitability but also more competition.

* Reviews impact pricing strategies and listing desirability, helping hosts optimize and improve guest satisfaction.

* Airbnb rentals are mostly short-term, with few requiring 30+ nights. Investing in properties for shorter stays can boost occupancy. Availability varies by neighborhood and room type, with shared rooms available most days annually.

* Future analysis can enhance predictive modeling, data integration, and personalized recommendations, improving market insights, evaluating impacts, and enhancing user experience.

