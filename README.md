# Food Sales Predictions 
<img width="1114" alt="Screen Shot 2023-04-11 at 2 26 35 AM" src="https://user-images.githubusercontent.com/125938742/231074321-cd005f1b-1eb3-440a-8ea9-951479172106.png">
Analyzing the highest and lowest prices in food sales 


## Date Dictionary 
<img width="595" alt="Screen Shot 2023-04-11 at 2 30 43 AM" src="https://user-images.githubusercontent.com/125938742/231075147-9ac3c9c5-d42e-4bce-ab4a-5c21411ad25c.png">

Heatpam of the different features 

![](https://github.com/nour614/food-sales-prediction/blob/main/sales%20heatmap.png)

This heatmap displays the correlation between various features of the sold items. Based on the heatmap, we can observe that there is a low correlation between Item Outlet Sales and the other features, except for Item MRP which has the highest correlation coefficient of 0.57. This suggests that Item MRP is a significant predictor of Item Outlet Sales, while the other features may have less impact on sales

### To prepare this data, the data was cleaned, and the following processes were performed:

- Exploratory Data Analysis
- Explanatory Data Analysis
- Machine Learning Using the Following Models:
   1. Linear Regression Model
   2. Decision Tree Regressor Model
   3. Tuned Decision Tree Regressor Model
   4. Bagging Tree Regressor Model
   5. Tuned Bagged Tree Regressor Model 


## Models Evaluated & Results
### Linear Regression Model (Testing Set):
- MAE: 804.1181 
- MSE: 1,194,347.6143 
- RMSE: 1,092.8621 
- R2: 0.5671
### Decision Tree Regressor Model (Testing Set):
- MAE: 1,039.4660 
- MSE: 2,229,281.3931 
- RMSE: 1,493.0778 
- R2: 0.1920
### Tuned Decision  Tree Test Scores
- MAE: 738.3173 
- MSE: 1,118,185.9731 
- RMSE: 1,057.4431 
- R2: 0.5947
### Bagged Tree Test Scores
- MAE: 797.2335 
- MSE: 1,328,901.9767 
- RMSE: 1,152.7801 
- R2: 0.5183
### Tuned Bagged Tree Test Scores
- MAE: 778.9824 
- MSE: 1,266,195.7785 
- RMSE: 1,125.2537 
- R2: 0.5411

From the results The Tuned Decision Tree has higher r2 score of (.59) which gives us a 
closer prediction.


