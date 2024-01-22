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

### For further information:

#### For any additional questions, please contact: wkylepridgen@gmail.com
