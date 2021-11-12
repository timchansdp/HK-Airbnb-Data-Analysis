# Hong Kong Airbnb Data Analysis



## Table of Contents
1. [Project Motivation](#1-project-motivation)
2. [Dependencies](#2-dependencies)
3. [File Structure & Description](#3-file-structure--description)
4. [Analysis Results](#4-analysis-results)
5. [Acknowledgements](#5-acknowledgements)



## 1. Project Motivation
The objective of this project is to analyze the open-source Hong Kong Airbnb data by employing statistics and visualizations so that five business questions can be compellingly answered:

Q1. Which neighborhood has the greatest potential of maximizing the revenue?
Q2. Is being a super host worthy?
Q3. Which month is best for visits in terms of availability and pricing?
Q4. Which neighborhood you should start looking into first in terms of the variety of choices?
Q5. What are the impact of the 2019 Hong Kong protests and the COVID-19 pandemic from the Airbnb perspective?

This analytics provides an overview of some aspects of the Hong Kong Airbnb market, It can also serve as a guide to all future hosts and visitors, as it answers questions such as the seasonality of availability, or how the super host status influences the revenue.



## 2. Dependencies
The code is developed with Python 3.7.12 and is dependent on python packages listed as below:
matplotlib == 3.2.2
numpy == 1.19.5
pandas == 1.1.5
seaborn == 0.11.2
statsmodels == 0.10.2



## 3. File Structure & Description
~~~~~~~
|-- data
    |-- calendar.csv # detailed Calendar Data for Hong Kong
    |-- listings.csv # detailed Listings data for Hong Kong
    |-- reviews_summary.csv # summary of review data with listing ID for Hong Kong
|-- figures # contains visualizations generated by the jupyter notebook
|-- Submission_EDA_of_HK_Airbnb.ipynb # exploratory & explanatory data analysis for Q1-5
|-- README.md
~~~~~~~



## 4. Analysis Results
The main findings of this project is presented in a medium blog post available [here](https://medium.com/@timchansdp/testing-259fbaa7742f).



## 5. Acknowledgements
[Inside Airbnb](http://insideairbnb.com/get-the-data.html) is created with the listings data used in this project. Inside Airbnb is a mission driven activist project with the objective to provide data that quantifies the impact of short-term rentals on housing and residential communities; and also provides a platform to support advocacy for policies to protect our cities from the impacts of short-term rentals.
