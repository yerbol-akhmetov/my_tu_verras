# Welcome to My Tu Verras
***

## Task
The problem is to create a machine learning model based on linear regression that predicts the price of a house based on the number of rooms it has. 

## Description
To solve the problem, we have taken the following sequence of steps: 
- First, we have loaded the data from a csv file into a Pandas dataframe
- Second, we have analyzed the columns of the dataframe and obtained its statistical summary
- Third, we have cleaned the data by eliminating any rows with NULL entries
- Fourth, we have done a visual analysis of the data by plotting them in histograms
- Fifth, we have analyzed the correlation between every pair of attributes by plotting them in a scatter-matrix
    - We have tried to spot a linear correlation between the attribute MDEV and other attributes such as LSTAT, AGE, CRIM
    - We have observed a positive linear trend in MDEV (price) with an increase in RM (# of rooms)
- Sixth, we have trained a linear regression model with RM as an input and MDEV as a target to predict the price based on the # of rooms
- Seventh, we have tested our model by giving a list of numbers of rooms and predicted their corresponding prices. 
- Finally, we have evaluated the performance of our model using MAE, MSE, RMSE. 

## Installation
The project should be executed in the Jupyter Notebook environment

## Usage
Upon execution, the project will import necessary libraries and call the following functions one by one:load_dataset, print_summarize_dataset, clean_dataset, print_histograms,compute_correlations_matrix,print_scatter_matrix,boston_fit_model, boston_predict and they will execute the commands listed under the 'Description' section of this READme. 

### The Core Team
Yerbol Akhmethov
Galymzhan Zharas

<span><i>Made at <a href='https://qwasar.io'>Qwasar Silicon Valley</a></i></span>
<span><img alt='Qwasar Silicon Valley Logo' src='https://storage.googleapis.com/qwasar-public/qwasar-logo_50x50.png' width='20px'></span>
