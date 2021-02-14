# Cryptocurrencies

## Project Overview
 Accountability Accounting requested a project was about cryptocurrencies and how they are performing on the trading market. They also wanted to now how cryptocurrencies can be grouped to create a classification system for their new investment. To build the report, we used the Unsupervised Machine Learning model to:
 
 - Preprocess Data for PCA.
 - Reduce Data Dimensions using PCA. 
 - Clustered Cryptocurrencies using K-means.
 - Visualized Cryptocurrency results. 
 
 ## Resources
 Data Source: crypto_data.csv
 Software: Python 3.8.3
 
 ## Summary
We created several data frames where we dropped null columns, removed unnecessary columns, changed columns to numerical values, and used the StandardScaler to standardize freatures in order to preprocess the data to perform PCA. Once we were able to format appropriately, we reduced the data (and made another df) to fit three pricipal components. We then created an elbow curve (seen below) to find the best value for our K clusters. 

![Screen Shot 2021-02-13 at 8 06 44 PM](https://user-images.githubusercontent.com/71476009/107866467-01f4a900-6e37-11eb-85b8-1d8903852e07.png)

We then made another dataframe where we concatenated our two previous data frames, added new columns and used this new df to create scatter plots and vizualize the cryptocurrency data (seen below) in a cohensive, digestable manner for Accountantability Accounting.

![Screen Shot 2021-02-13 at 8 17 01 PM](https://user-images.githubusercontent.com/71476009/107866632-7da32580-6e38-11eb-8fc3-65625f08c2c0.png)

![Screen Shot 2021-02-13 at 8 17 21 PM](https://user-images.githubusercontent.com/71476009/107866637-8b58ab00-6e38-11eb-86d2-53ad05fe11f4.png)

## Results

 
