**Task 1: Term Deposit Subscription Prediction (Bank Marketing)**  
**Task Objective**

Predict whether a bank customer will subscribe to a term deposit based on historical marketing campaign data.
The goal is to improve campaign targeting and reduce marketing costs.

**Approach**

Performed data preprocessing with feature scaling and one-hot encoding

Built machine learning pipelines for reproducibility

Trained and evaluated:

Logistic Regression

Random Forest Classifier

Evaluated models using confusion matrix, precision, recall, and F1-score

**Results and Findings**

Random Forest achieved the best performance

Accuracy: 86%, F1-score (Subscribed class): 0.86

Model effectively identifies high-probability customers

Supports data-driven marketing decisions and cost reduction

**Task 2: Customer Segmentation Using Unsupervised Learning   **
**Task Objective**

Segment customers based on spending behavior to enable personalized marketing strategies.

**Approach**

Conducted Exploratory Data Analysis (EDA) on customer demographics

Selected key features: Age, Annual Income, Spending Score

Standardized data using StandardScaler

Applied K-Means clustering with optimal clusters determined by the Elbow Method

Visualized clusters using PCA

**Results and Findings**  

Customers segmented into 5 distinct clusters

Spending behavior does not always correlate directly with income

Clear cluster separation observed using PCA

Enables targeted marketing, improved engagement, and better resource allocation


** Task 3: Energy Consumption Time Series Forecasting **    
**Task Objective**  

Forecast short-term household energy consumption using historical time-series data and compare statistical and machine learning models.

**Approach**

Parsed and resampled energy consumption data to hourly frequency

Applied time-based train–test split

Trained and compared:

ARIMA

Prophet

XGBoost with time-based and lag features

Evaluated models using MAE and RMSE

Visualized actual vs forecasted consumption

**Results and Findings**    

Model	MAE	RMSE
ARIMA	0.68	0.91
Prophet	0.71	0.94
XGBoost	0.34	0.51

XGBoost delivered the most accurate forecasts

Feature engineering significantly improved model performance

Machine learning models outperformed classical statistical approaches

** Overall Summary**

Demonstrates strong understanding of supervised, unsupervised, and time series modeling

Shows ability to translate data insights into business value
