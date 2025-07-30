# knn-freedom-predictor
**Utilized the World Happiness Dataset to build a K-Nearest Neighbors (KNN) regression model predicting “Freedom to make life choices” based on socioeconomic and perception-based features.
**
## Data Preprocessing & Feature Engineering:
- Applied Winsorization to reduce the impact of outliers
- Conducted feature scaling for this distance-scaled model to increase metrics 
- Performed data cleaning to remove or impute missing values or columns with high NA count
- Conducted feature engineering to enhance predictive signal
- Used one-hot encoding for 'country' and organized each country into their appropriate 'Region_' column
  
## Metrics:
- Achieved an R² score of 0.65, indicating a moderate-to-strong fit between predicted and actual values
