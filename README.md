# Prediction-of-Product-Sales
It is a project aims to predict sales of different items. The project is based on analyzing previous data containing different numeric, categorial, and ordinal features. 
## Project Author: Mohammed Alsayed
## Business Problem:
The business owners want to understand what are the most influencing features in the overall outlet sales.
## Data Describtion:
The analyzed data contains 8523 rows and 12 features. the predicting features consist of seven objects, three floats, and two integers. The target outlet sales feature type is float. The dataset contained many problems, including missing values, inconsistancy, and outliers. Therefore, it required cleaning steps.
Data dictionary is:
![Screenshot 2023-10-05 160326](https://github.com/MoAlsayed/Prediction-of-Product-Sales/assets/144434790/86699496-0b04-40fc-97b1-899cdde09a6d)
## Methods: 
Detailed data exploration through visulization and correlation analysis were implemented to define the most influencing features.
Then linear regression and random forests algorithms were used to build predicting models.
The project implementation methodology contains systematic data cleaning steps.
Data analysis first step was statistical and exploratory visual. 
![four-components-data-cleaning-four-components-data-cleaning-200203791](https://github.com/MoAlsayed/Prediction-of-Product-Sales/assets/144434790/77a2d0f2-0bc9-4864-a646-c7c62c4c9532)
## Results:
Linear Regression and Random forests algorithms did well but not excellent, where R2 values ranged approximately between 0.5 to 0.7. However, visualization and correlation analysis consluded that:
- catoegorial features to be included in the model are:
  - Outlet_Identifier
  - Outlet_Type
- numeric features to be included in the model are:
  - Item_Weight
  - Item_Visibility
  - Item_MRP
Sample of plots:
![prediction project matrix](https://github.com/MoAlsayed/Prediction-of-Product-Sales/assets/144434790/757a5bc9-0347-433e-93b6-5321c69896f2)
![corr prediction project](https://github.com/MoAlsayed/Prediction-of-Product-Sales/assets/144434790/17e36f3b-a261-403e-8454-72321c5084e3)
![categorial vs target](https://github.com/MoAlsayed/Prediction-of-Product-Sales/assets/144434790/dd461e73-184f-4f7c-b0ab-f9bec40b05eb)

## Limitations and Next Steps:
The project needs final tuning, steps review, and further prediction algorithms tuning.



 

