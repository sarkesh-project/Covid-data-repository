# Covid-data-repository
# COVID-19 Data Pipeline Project

## Overview
This project builds a data pipeline to analyze and predict COVID-19 case trends using **Pandas** and **Scikit-learn**. It downloads COVID-19 data from Our World in Data, cleans and preprocesses the data, performs exploratory data analysis, and uses a machine learning model to predict new daily cases.

## Features
- Data ingestion from a live public dataset
- Data cleaning and preprocessing (handling missing data, feature engineering)
- Exploratory data analysis with visualizations
- Simple predictive model using Random Forest Regressor
- Evaluation of model performance with MAE (Mean Absolute Error)
- Reusable pipeline structure for easy updates with new data

## Dataset
Data source: [Our World in Data COVID-19 Dataset](https://covid.ourworldindata.org/data/owid-covid-data.csv)  
The dataset includes daily cases, deaths, testing data, and other socio-economic indicators globally.

## Getting Started

### Prerequisites
Make sure you have Python 3.x installed along with the following libraries:

```bash
pip install pandas scikit-learn matplotlib
