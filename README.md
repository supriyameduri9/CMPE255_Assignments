# CMPE255_Assignment-1

Steps followed in the assignment are described below 

* I picked up Delhi House Price Prediction dataset from kaggle. It has 11 columns and 1259 rows and is fairly noisy.
* Link to dataset : https://www.kaggle.com/neelkamal692/delhi-house-price-prediction.
* Firstly necessary libraries are imported and the file is loaded to perform data cleaning.
* I found null values and considered only unique values.
* Unecessary columns which dont contribute to the model are dropped.
* Dropped rows which have 'Locality' value more than 200.
* Grouping the data based on locality. I picked up few localities which are redundant and replaced them to be called under same locality.This helped in the decreasing the unique values of 'Locality' from 365 to 158
* In the area, I grouped all the values of area based on a range. Replaced values with 'Area' between 100 - 1000 sqft as 1, 1001 - 2000 sqft as 2 and so on..
* Plotted a barplot with 'Area vs House Count'.
* Finally dropped rows with any null values. Thus the cleaned data can be used for further processing.
