# PyBer_Analysis

# Overview of the analysis 
The purpose of the analysis is to find how data differs by city type and how those differences can be used by decision-makers in PyBer.

### Resources
Data source: [city_data.csv](https://github.com/xenia-e/PyBer_Analysis/blob/main/Resources/city_data.csv), [ride_data.csv](https://github.com/xenia-e/PyBer_Analysis/blob/main/Resources/ride_data.csv)

### Methods
We performed the analysis on the provided datasets using Python, Jupyter Notebook, and Matplot library. 

### Deliverables 
- **Deliverable 1**: [A ride-sharing summary DataFrame by city type](https://github.com/xenia-e/PyBer_Analysis/blob/main/PyBer_Challenge.ipynb)
- **Deliverable 2:** [A multiple-line chart of total fares for each city type](https://github.com/xenia-e/PyBer_Analysis/blob/main/Analysis/PyBer_fare_summary.png)
- **Deliverable 3:** A written report for the PyBer analysis [README.md](https://github.com/xenia-e/PyBer_Analysis/blob/main/README.md)

# Results

__Referring to the "Ride-sharing Summary by City Type" and "Total Fare by City Type" figures we can assume that ride-sharing is more popular in urban cities.__

![A ride-sharing summary DataFrame by city type
](https://github.com/xenia-e/PyBer_Analysis/blob/main/Analysis/PyBer_Challenge%20-%20Summary.png)

>Figure - 1. Ride-sharing Summary by City Type. 

![Total Fare by City Type
](https://github.com/xenia-e/PyBer_Analysis/blob/main/Analysis/PyBer_fare_summary.png)

>Figure - 2. Total Fare by City Type. 

Urban cities have **the lowest fare per ride**. None the less the **Total Fare** is almost **ten times higher** than it is in the other types of cities. The average number of drivers in urban cities is four to nine times greater than in suburban rural cities, respectively. Also, the average number of rides in urban cities is about 4-times greater than in suburban and rural cities.

We can assume all this is a result of the larger population in urban cities. And average fare per ride in rural and suburban cities is higher because of the longer ride distance. To prove this assumption we should calculate percentages of pyBer users to the average population in that region. And calculate the average fare per mile or kilometer to determine if it is indeed higher for the suburban and rural cities. 


# Summary

As a summary of the performed analysis, we can suggest the following:
1. Make mentioned above additional calculations to get into the nature of differences in performance between different types of cities.
2. Based on the additional data adjust fare prices for rides depending on the distance.
3. Popularise ride-sharing in suburban and urban cities if projected total fares growth will cover marketing expenses.  

