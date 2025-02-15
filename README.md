# us-road-accidents-analysis-DA-project
US Accidents Exploratory Data Analysis For Data Analysis Project

## Project Context
This project analyzes road accident data from the United States to uncover patterns, trends, and contributing factors. The goal is to provide insights that could aid in improving road safety and traffic management. Through exploratory data analysis (EDA), we examine factors like accident frequency, time of day, and accident severity.

## Outcomes
- Identified peak times and days for accidents.
- Visualized accident frequency across states and cities.
- Gained insights into the relationship between traffic density and accident rates.

## Pre-requisites
Before running the analysis, make sure you have the following installed:

- Python 3.x
- Google Colab (or Jupyter Notebook)
- Required Python libraries:
  - `pandas` (for data manipulation)
  - `matplotlib` (for data visualization)
  - `seaborn` (for advanced visualizations)
  - `numpy` (for numerical operations)
  - `scikit-learn` (optional, if you apply machine learning models)
 
  ### Installation
    
Install the library using pip:

pip install opendatasets --upgrade

### Usage - Downloading a dataset

Datasets can be downloaded within a Jupyter notebook or Python script using the opendatasets.download helper function. Here's some sample code for downloading the US accidents Dataset:

import opendatasets as od

dataset_url = 'https://www.kaggle.com/tunguz/us-accidents-dataset'

od.download('https://www.kaggle.com/tunguz/us-accidents-dataset')


### Kaggle Credentials

opendatasets uses the Kaggle Official API for donwloading dataset from Kaggle. Follow these steps to find your API credentials:

Go to https://kaggle.com/me/account (sign in if required).

Scroll down to the "API" section and click "Create New API Token". This will download a file kaggle.json with the following contents:

{"username":"YOUR_KAGGLE_USERNAME","key":"YOUR_KAGGLE_KEY"}

When you run opendatsets.download, you will be asked to enter your username & Kaggle API, which you can get from the file downloaded in step 2.

Note that you need to download the kaggle.json file only once. You can also place the kaggle.json file in the same directory as the Jupyter notebook, and the credentials will be read automatically.


### Local Development Setup

Clone the repository:

git clone https://github.com/Nens1N/us-road-accidents-analysis-DA-project/tree/main

Setup the Python environment for development

conda create -n opendatasets python=3.5

conda activate opendatasets

pip install -r requirements.txt

Open up the project in VS code and make your changes. Make sure to install the Python Extension for VS Code and select the opendatasets conda environment.
 
  
