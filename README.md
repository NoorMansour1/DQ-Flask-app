# DQ-Flask-app

## Description
This simple Flask app creates a Data Quality dashboard, conducting data profiling on a loaded pandas dataframe. For each column, the report analyzes not only quantile and descriptive statistics but also type inference, unique values, missing values, correlations duplicate rows and creates histograms. The main library used to create the report is [pandas-profiling](https://pandas-profiling.ydata.ai/docs/master/pages/getting_started/overview.html). 
The sample data the report is generated on is loaded into the application as a pickle file ```aseas_data.pick```. Configurations on the report can be made by modifying the ```config.json``` file. 

## How to install and run the Flask application

### Installation
Use pip and the requirements.txt to install the necessary libaries.

```pip install -r requirements.txt ```

### Run the Flask server
Use the following command to run the flask server: 
 
```flask run ```

Pleae refer to the flask documentation for more flags and options. 
