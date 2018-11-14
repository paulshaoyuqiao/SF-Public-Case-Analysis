# SF-Public-Case-Analysis
This is an exploratory analysis of the San Francisco public service cases over the past few years. 

Please see `Analysis.ipynb` for details.

The problem I am trying to investigate is predicting statuses of the case requests from their other characteristics (such as request categories, locations, etc.)

The analysis is divided into the following parts:

The analysis consists of primarily 4 parts:

* Importing & Editing Data

1. Importing CSV and Overview of the DataFrame
2. Analysis of the Null Values
3. Choosing the Problem/Characteristics to Investigate

* Exploratory Data Analysis

1. Overview of Statuses of Requests
2. Statuses of Requests and Request Categories
3. Statuses of Requests and Request Sources
4. Statuses of Requests and Request Locations

* Determining and Implementing the ML Model

1. Cleaning & Restructuring Data (Re-aggregated Categories & One-hot Encoding)
2. Random Forest Classification - Request Categories & Sources (as Input)
3. K-Nearest Neighbors Classification - Request Locations
4. Stacking ML Models

* Further Exploratory Analysis

1. Exploring & Transforming the Opened and Closed Time Columns
2. Distribution of the Days Elapsed for All the Requests
3. Days Elapsed v. Re-aggregated Categories
4. Days Elapsed v. Request Sources




