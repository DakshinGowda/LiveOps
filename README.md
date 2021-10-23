# LiveOps

## Introduction
In this notebook, we will conduct exploratory data analysis using Pandas and Seaborn to find hidden patterns behind Ride Monitoring Process and to reduce First Station Lateness. We will also develop a basic understanding of ride quality of existing customers in online bus ticketing platform and understand how data is used to optimize the process of ride monitoring process.

## Business Understanding
The LiveOps team in SWVL manages the day to day ride monitoring and ride saving activities for all the markets across the globe. There are agents in the LiveOps team that call captains every day before the ride with periodic intervals i.e. 60 mins prior, 45 mins prior and 30 mins prior to the ride to ensure that captains are aware of their next ride(s) and have confirmed the ride on the app so customer have the assurance that they will be taken to their desired destinations.

There are instances where the captains confirm on the call to the Agent and on the app that they will take the ride but don’t show up at the first station on ground. These rides are usually cancelled and their reasons are tagged for understanding the magnitude of the issue at hand. With our business expanding across different markets, the ride count will organically increase which also means agent headcount would be directly impacted.

## Problem Statement
It would be great to know your thought process and strategy to solve for the following problem statements:
- Reducing the direct relationship between scalability of business with agent headcount.
- Increasing the success rate of calls on T-60, T-45, and T-30 intervals.
- Developing strategies to reduce ride cancellations and increase ride confirmations through app i.e. Ride_Confirmation_Status to be Captain thru App.
- Plotting a process to improve captain quality to reduce instances of lateness.

## Document
- [Dataset](https://github.com/dakshingowda/LiveOps/blob/main/Live%20Ops%20Case%20Study.xlsx)
- [Notebook](https://github.com/dakshingowda/LiveOps/blob/main/Live%20Ops%20-%20DataAnalysis.ipynb)

## Trend analysis
<p align="center"><img src = 'https://github.com/dakshingowda/LiveOps/blob/main/Images/Trend%20over%20a%20period%20of%20time.png' width = 600><p>
