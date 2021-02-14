# Cryptocurrencies

## Project Overview
 Accountability Accounting requested a report about cryptocurrencies and how they are performing on the trading market. They also wanted to understand how cryptocurrencies can be grouped to create a classification system for their new investment. To build the report, we used the Unsupervised Machine Learning model to:
 
 - Preprocess Data for PCA.
 - Reduce Data Dimensions using PCA. 
 - Cluster Cryptocurrencies using K-means.
 - Visualize Cryptocurrency results. 
 
 ## Resources
 Data Source: crypto_data.csv
 Software: Python 3.8.3
 
 ## Summary
We created several data frames where we dropped null columns, removed unnecessary columns, changed columns to numerical values, and used the StandardScaler to standardize freatures in order to preprocess the data to perform PCA. Once we were able to format appropriately, we reduced the data (and made another df) to fit three pricipal components to create a more easily digestible report. We then created an elbow curve (seen below) to find the best value for our K clusters. 

![Screen Shot 2021-02-13 at 8 06 44 PM](https://user-images.githubusercontent.com/71476009/107866467-01f4a900-6e37-11eb-85b8-1d8903852e07.png)

Next, we made another dataframe where we concatenated our two previous data frames, added new columns and used this new df to make predictions and to create scatter plots and a 3D visualization of the cryptocurrency data (seen below) for the Accountantability Accounting team.

![Screen Shot 2021-02-13 at 8 17 01 PM](https://user-images.githubusercontent.com/71476009/107866632-7da32580-6e38-11eb-8fc3-65625f08c2c0.png)

![Screen Shot 2021-02-13 at 8 20 39 PM](https://user-images.githubusercontent.com/71476009/107866691-fbffc780-6e38-11eb-9b01-c145f6b41bf3.png)

![Screen Shot 2021-02-13 at 8 17 21 PM](https://user-images.githubusercontent.com/71476009/107866637-8b58ab00-6e38-11eb-86d2-53ad05fe11f4.png)


 
