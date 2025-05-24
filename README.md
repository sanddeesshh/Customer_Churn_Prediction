# My Customer Churn Prediction Project

This is a project I built to predict if a customer will stop using a service. It's based on data from a telecom company.

## What this project is about

Businesses want to know when customers might leave so they can try to keep them. My goal with this project was to use machine learning to find out which customers are likely to churn.

## The data I used

I worked with a dataset about telecom customers. It includes things like:

- Customer details (like if they are male or female, or a senior citizen)
- What services they have (like phone or internet)
- How they are billed (like how much they pay each month)
- And importantly, whether they actually left the company

## How I did it

Here's a simple outline of my steps:

1.  I loaded the data and looked at what was in it.
2.  I explored the data to understand the trends and patterns.
3.  I prepared the data for the model, handling things like missing information and getting the data into the right format. I also used a technique called SMOTE to help with the fact that more customers stayed than left.
4.  I trained a few different machine learning models.
5.  I chose the Random Forest model because it performed well.
6.  I tested the model on data it hadn't seen before to see how accurate it was.
7.  I saved the trained model and some other necessary information.

## The model I used

I used a Random Forest model for the prediction.

## What's in this repository

-   The main code is in a notebook file.
-   The data I used is also here.
