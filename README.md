# Analyze_wheat_product

## I) Reason

After the US-Iran tension, the price of old and natural gas is increasing creating power price increase which creating inflation. But in the corner, there have 2 field is also very dangerous to national industry is chemical and agriculture and agriculture is the most important because it will create a worst event is starvation. This is the reason of this project    

## II) Purpose

This project is showing the data processing process, explore data inside and predict result to saw all the impact to the price of wheat product like how fertilize and chemical impact to the food price in this case is wheat

## III) Source

Kaggle: https://www.kaggle.com/datasets/ranamuhammmadusman/wheat-economics-comprehensive-farm-data

## IV) Path tree


Directory: dataset
Purpose: contain raw data need to be clean and process
Data type: csv
[dataset](https://github.com/johnluk0092/analyze_wheat_product/tree/main/dataset)

Directory: data warehouse
Purpose: contain cleaned data ready to analyze 
Data type: parquet
[data warehouse](https://github.com/johnluk0092/analyze_wheat_product/tree/main/data_warehouse)

File: data cleaning and processed (Extract, Load, Transform)
Purpose: Extract raw data from source, Loading the raw data for the process, Transform data from raw data to ready to analyze data
File type: ipynb
Language: Python
Library: numpy, pandas, matplotlib, seaborn, os
[data processing ELT](https://github.com/johnluk0092/analyze_wheat_product/blob/main/p_Wheat_economics_cleaning_ELT.ipynb)

File: data analyze and forecast 
Purpose: reprocess data, data understanding, perform EDA, feature engineering, training model, evaluation, model selection
File type: ipynb
Language: Python
Library: numpy, pandas, matplotlib, seaborn, sklearn, os
[analyze and model forecast](https://github.com/johnluk0092/analyze_wheat_product/blob/main/p_Wheat_economics.ipynb)

## V) Result

This project to have the full view of the data, model and forecast to have the better judgment on the next move. After training and selecting to have the best model with the good score and avoid underfitting and overfitting :

* train_r_square: 0.950407 	 	 	 	 	
* test_r_square: 0.899
* MSE: 0.054596 	
* RMSE: 0.233657 	
* MAE: 0.169211 	
* adj_r_square: 0.735846
