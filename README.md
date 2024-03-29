# Sprint_6_project

## Analyzing Zuber's passenger behavior

# Project description
You're working as an analyst for Zuber, a new ride-sharing company that's launching in Chicago. Your task is to find patterns in the available information. You want to understand passenger preferences and the impact of external factors on rides.

Working with a database, you'll analyze data from competitors and test a hypothesis about the impact of weather on ride frequency.

![image](https://github.com/nhayenquynh/Sprint_6_project/assets/125513684/5709b91e-deed-4889-a90a-81b61490461b)

# Instructions/Questions to be answered: 

**Write a code to parse the data on weather in Chicago in November 2017 from the website**
https://practicum-content.s3.us-west-1.amazonaws.com/data-analyst-eng/moved_chicago_weather_2017.html

**Exploratory data analysis (SQL)**
1. Find the number of taxi rides for each taxi company for November 15-16, 2017. Name the resulting field trips_amount and print it along with the company_name field. Sort the results by the trips_amount field in descending order.
2. Find the number of rides for every taxi company whose name contains the words "Yellow" or "Blue" for November 1-7, 2017. Name the resulting variable trips_amount. Group the results by the company_name field.
3. In November 2017, the most popular taxi companies were Flash Cab and Taxi Affiliation Services. Find the number of rides for these two companies and name the resulting variable trips_amount. Join the rides for all other companies in the group "Other." Group the data by taxi company names. Name the field with taxi company names company. Sort the result in descending order by trips_amount.

**Test the hypothesis that the duration of rides from the the Loop to O'Hare International Airport changes on rainy Saturdays.**

1. Retrieve the identifiers of the O'Hare and Loop neighborhoods from the neighborhoods table.
2. For each hour, retrieve the weather condition records from the weather_records table. Using the CASE operator, break all hours into two groups: "Bad" if the description field contains the words "rain" or "storm," and "Good" for others. Name the resulting field weather_conditions. The final table must include two fields: date and hour (ts) and weather_conditions.
3. Retrieve from the trips table all the rides that started in the Loop (neighborhood_id: 50) and ended at O'Hare (neighborhood_id: 63) on a Saturday. Get the weather conditions for each ride. Use the method you applied in the previous task. Also retrieve the duration of each ride. Ignore rides for which data on weather conditions is not available.

**Exploratory data analysis (Python)**
1. Study the data 
2. Make sure data types are correct
3. Identify the top 10 neigboorhoods in terms of drop-offs
4. Make graphs: taxi companies and number of rides, top 10 neighborhoods by number of dropoffs
5. draw conclusions based on each graph and explain the results

**Testing hypotheses (Python)**
Test the hypothesis: "The average duration of rides from the Loop to O'Hare International Airport changes on rainy Saturdays."
- Set the significance level (alpha) value on your own.

Explain:
- how you formed the null and alternative hypotheses
- what criterion you used to test the hypotheses and why

# Generated Chart: 
<img width="908" alt="image" src="https://github.com/nhayenquynh/Zuber-s-Passenger-Analysis-/assets/125513684/0c54b699-2bc9-4592-8b28-29af9366a098">


