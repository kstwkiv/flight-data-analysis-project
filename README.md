![image](https://github.com/user-attachments/assets/58efc1b9-f546-493e-9fbc-44f9060ad13c)# Flight Data Analysis

## Introduction

This repository contains the exploratory data analysis (EDA) of a dataset detailing airline flights. 

The dataset includes various attributes of flights such as airline, flight number, departure and arrival times, stops, class, duration, days left until departure, price, and date of the flight.

## Dataset

The dataset consists of 3,11,078 rows and 13 columns. Below are the columns present in the dataset:

Unnamed: 0: An index column (can be ignored)

airline: The airline operating the flight

flight: The flight number

source_city: The city from which the flight departs 

departure_time: Time of day the flight departs (Morning, Afternoon, Evening, Night)

stops: Number of stops (zero, one, two_or_more)

arrival_time: Time of day the flight arrives (Morning, Afternoon, Evening, Night)

destination_city: The city where the flight arrives 

class: The class of travel 

duration: Duration of the flight in hours

days_left: Number of days left until the flight's departure

price: The price of the flight ticket

date: The date of the flight in the format dd-mm-yyyy


## Methodology

The data analysis process involves the following steps:

Loading the data: Reading the data from a CSV file into a pandas DataFrame.

Data Cleaning: Handling missing values, correcting data types, and removing any unnecessary columns.

Data Visualization: Using libraries like matplotlib and seaborn to create visualizations that help understand the distributions and relationships within the data.

Summary Statistics: Generating descriptive statistics for numerical and categorical columns.

## Example visualizations

The data analysis script will generate various plots, such as:

Distribution of flight prices

Flight duration vs. price

Number of flights per airline

Price variation over time

Distribution of flights by departure time and arrival time

## Conclusion 

By applying data analysis techniques to this comprehensive dataset, this study aims to provide a deeper understanding of the complex dynamics driving the aviation industry, ultimately informing data-driven decisions that can improve customer satisfaction, increase revenue, and enhance operational efficiency.

Arrival Times: Most flights arrived at night, followed by morning, afternoon, and evening.

Departure Times: Most flights departed in the morning, followed by evening, afternoon, and night.

Ticket Prices: The maximum ticket price was 2,512,780, and the minimum ticket price was 5,949.
