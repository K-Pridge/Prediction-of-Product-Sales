# Outlet Year vs Outlet Sales Predictions

## Using Machine Learning Models

#### Author: Kyle Pridgen

### Business Problem:

#### How do Item Outlet Sales contribute to the establishment year of the facility?

### Data: (csv_included)

#### DataFrame = '/content/drive/MyDrive/Colab Week 1/sales_predictions_2023.csv'

## Methods
  - Visualize specific columns for better understanding
  - Seaborn stripplot for Outlet_Establishment_Year vs Item_Outlet_Sales

## Results
![Stripplot Outlet _Year vs Outlet_Sales](https://github.com/K-Pridge/Prediction-of-Product-Sales/assets/135768523/f970cfa0-1fb7-4022-822d-47ef99e7ca36)


# Prediction-of-Product-Sales

### Model 
  - Seaborn heatmap to show negative to positive strenghts of all correlating variables
  - Item MRP value contributes to over fifty percent of Item Outlet Sales
  - Using a tuned Random Forest Model creates an R^2 Score of 0.59 on the Training Data, meaning that the model properly predicts correct MRP to Item Outlet Sales

## Results
![sns heatmap(README)](https://github.com/K-Pridge/Prediction-of-Product-Sales/assets/135768523/ac8feede-ff31-4b3d-b2c6-3b34d2de7e92)

## Recommendations
 - Continue tuning various models on the Training and Testing Data (Confusion Matrix, ROC/AUC, etc.)
 - Item Outlet Sales as the target for each

## Next Steps:
  - Continue tuning data set through various Regression Models


## Linear Coefficient Model 
![Lin_Reg Plot](https://github.com/K-Pridge/Prediction-of-Product-Sales/assets/135768523/dce5ca6f-3dc7-439d-bc41-3e0d3cb3336c)

### Summary
- The type of Supermarkey affects outlet sales by just under 600 annually. 
- The location affects sales by over 200 annually.
- The types of foods available(seafood, breakfast items, low fat foods, vegetables and fruits) affects item sales from 25-100 annually.


## Tree-Based Model
![ItemOutletSales_Features Plot](https://github.com/K-Pridge/Prediction-of-Product-Sales/assets/135768523/3fb7912f-355c-45fd-889e-c113675a37ea)

### Summary
- The top 5 most important feature are: MRP, Type of Grocery Store, Item Visibility, Item Weight and Outlet Identifier.
- These features contribute the most positively to the increase of Item_Outlet_Sales.



### For further information:

#### For any additional questions, please contact: wkylepridgen@gmail.com
