# 🔥 California Wildfire Prediction Model

## 🌎 Overview
* This project leverages machine learning techniques to predict wildfire risks in California using historical data, weather metrics, and environmental features. By accurately identifying high-risk areas, this model aims to assist emergency responders, researchers, and policymakers in mitigating wildfire damage.

### 📁 Project Structure
* California Wildfire Prediction Model.ipynb – Main notebook containing data preprocessing, model training, evaluation, and visualizations

* data/ – Contains CSV files with wildfire records and weather data

* output/ – Stores visualizations and prediction results (created after running the notebook)

* models/ – (Optional) Trained models can be saved here for reuse



## 🧠 Machine Learning Approach
### The model pipeline includes:

* Data cleaning and merging of wildfire and weather datasets

* Feature engineering (date parsing, normalization, etc.)

* Train-test split with stratification

* Model training with Random Forest

* Model evaluation using classification metrics

📈 Model Performance
* After training the Random Forest classifier:

* Accuracy: 88.5%

* Precision: 84.3%

* Recall: 90.2%

* F1 Score: 87.1%

* ROC-AUC Score: 0.91

* These results show strong generalization and balance between false positives and false negatives — essential for emergency response planning.

### 📊 Visualizations
* Correlation heatmap of features
* Fire occurrence frequency over time
* Feature importance ranking
* Confusion matrix and classification report
* Predicted fire risks mapped by region (if coordinates are present)

