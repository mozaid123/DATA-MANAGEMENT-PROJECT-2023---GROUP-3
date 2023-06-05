# RENT PRICES IN LIEGE
Note : The final presentation and Jupyter notebook will be available later today (05/06/2023) due to some last minute inconviences with the code, thank you for understanding

## Motivation

This project was created with the aim of understanding, simplifying and predicting the task of looking for new accommadation to rent. We recognized the need for a roadmap that will allow students to conduct informed decisions in these testing times. 

## Data

The data used in this project is sourced from kotaliege.be and immoweb.be. The dataset was obtained through webscraping the websites and stocked in an excel file. It consists of type of accommodation, prices and zipcodes . The data was preprocessed and cleaned to ensure its quality and relevance for the project.

## Methodology

The methodology employed in this project follows a systematic approach to address the problem statement. The key steps involved are as follows:

1. **Data Collection**: The data was obtained from the mentioned websited through webscraping by the selenium package and stored in excel.

2. **Data Preprocessing**: The collected data underwent preprocessing steps such as cleaning and modifying some variable types in order to analyse them the most convientntly through Jupyter. These steps were taken to ensure the data's quality and prepare it for further analysis.

3. **Exploratory Data Analysis (EDA)**: EDA was performed to gain insights into the data and understand its characteristics. This involved visualization of the data sourced

4. **Data Modelling** : Using the regression method, we have succesfully predicted the average price for each region of liège

## Modelling

The prediction task in this project involves using regression to predict student housing rent prices in Liège. Regression is a supervised learning technique that aims to predict a continuous numerical value, in our case, the price of rent. The regression model is trained on a dataset of known prices and corresponding features, and then used to make predictions on new data

