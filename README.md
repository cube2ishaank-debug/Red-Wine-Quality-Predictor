# Red-Wine-Quality-Predictor
This project creates a classifier model that predicts the quality rating of red wine from 5-7 based on 11 inputs including fixed acidity, chlorides and pH. 

## Dataset
The ML model was created based on a dataset uploaded to [UCI ML Learning Repository](https://archive.ics.uci.edu/dataset/186/wine+quality) of red wines. 

<img width="181" height="656" alt="image" src="https://github.com/user-attachments/assets/6095da9f-7fcb-4e61-81e2-b47e188591ba"/>
<br/> Here, the y-value (target) is the quality, and the rest of the variables are x-values (inputs). This model uses all inputs listed on UCI apart from color as it only predicts the quality of red wine.
The model has 4898 instances with 11 features.
### Citing Source
<br/> 
Cortez, P., Cerdeira, A., Almeida, F., Matos, T., & Reis, J. (2009). Wine Quality [Dataset]. UCI Machine Learning Repository. https://doi.org/10.24432/C56S3T.

## The ML Model
### Linear Regression
The ML model created in this project uses linear regression to learn the patterns in the continous quantative dataset and predict the quality of the wine. The ML model uses 80% of the data for training while using 20% for testing the model. 
<br>
## Evaluating the Model
### Evaluating in Steps (5-7 Quality Index)
#### Graph
<img width="1990" height="1489" alt="image" src="https://github.com/user-attachments/assets/2dd8f43b-7553-493c-96c9-b8ab77ab42b6"/>

#### Analysis

--- Prediction Statistics Grouped by Actual Quality ---

Actual Quality 5:
  Mean of Predictions: 5.383
  Mean Absolute Deviation (MAD) of Predictions: 0.256

Actual Quality 6:
  Mean of Predictions: 5.757
  Mean Absolute Deviation (MAD) of Predictions: 0.341

Actual Quality 7:
  Mean of Predictions: 6.176
  Mean Absolute Deviation (MAD) of Predictions: 0.217

--- End of Analysis ---

### Total Evaluation

#### Graphs

##### Unsorted Data Comparison

<img width="1591" height="790" alt="image" src="https://github.com/user-attachments/assets/6fd90168-7cfb-442c-b3c0-352f8eb50150"/>

##### Sorted Data Comparison (Step-Filled)

<img width="1591" height="783" alt="image" src="https://github.com/user-attachments/assets/d54fcc8f-3c10-4f7f-83b1-b98c377e86dd"/>

### Analysis
--- Overall Model Metrics ---
<br>
Overall Mean of Predictions: 5.651
<br>
Overall Mean Absolute Deviation (MAD) of Predictions: 0.394
<br>
Overall R-squared (Coefficient of Determination): 0.403
<br>
Overall Mean Absolute Error (MAE): 0.504
<br>
--- End of Overall Analysis ---

## Checkout the Code!

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/14MLtLqWN01yTtHo-DUpzHC0Uf4srneMH#scrollTo=GQZhSMFdUE9I)
