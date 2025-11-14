Solar Radiation Prediction — Machine Learning Project

Predicting solar radiation using Linear Regression & Random Forest model 

Dataset: Solar Prediction (Kaggle)

Project Overview:
This project uses machine learning to predict solar radiation levels based on weather-related features such as temperature, humidity, pressure, and time of day.

Goals of the Project:
* Clean and prepare a real-world dataset
* Perform exploratory data analysis (EDA)
* Build and compare two machine learning models
* Interpret model performance using metrics and visualizations
* Identify the most important features influencing solar radiation

This project demonstrates my ability to take a dataset from raw form to the final model using a complete ML workflow.

Dataset:

Source: Kaggle — Solar Radiation Prediction

The dataset includes the following useful columns:
- Temperature
- Humidity
- Pressure
- Timestamp (converted to Hour, Month, Day)
- Radiation (target variable)
  
Data Cleaning & Preprocessing

Steps performed:

1. Removed missing values
2. Dropped duplicate rows
3. Converted the timestamp into a proper datetime format
4. Extracted useful time-based features:
Hour, Day and Month
5. Selected key predictive features for the model
These steps converted messy data into clean, model-ready inputs.

Exploratory Data Analysis (EDA)

I analyzed relationships between the variables using:
* Histograms
* Scatter plots
* Correlation insights


Machine Learning Models

1. Linear Regression

A simple baseline model to understand the basic relationship between features and radiation.
Metrics:
* R² Score
* Mean Absolute Error

2. Random Forest Regressor

A more powerful ensemble model using multiple decision trees.

Why Random Forest?
* Captures non-linear relationships
* Usually delivers higher accuracy
* Offers clear feature importance insights
  
Metrics:
* R² Score
* Mean absolute error
* Feature Importance Plot

Random Forest outperformed Linear Regression, making it the stronger model for this dataset.

Feature Importance

Using Random Forest, I identified which features matter most for predicting solar radiation.

This helps interpret the model and understand environmental patterns.

Technologies Used
* Python
* Pandas
* Matplotlib
* Scikit-Learn
* Jupyter Notebook
                    
What I Learned:

* Handling and cleaning real-world datasets
* Feature engineering
* Comparing different ML algorithms
* Evaluating models using R² and Mean absolute error
* Visualizing predictions and feature importance
* Explaining machine learning results clearly

Future Improvements

To enhance this project further, I could:
* Try other boosting algorithms
* Deploy the model using Flask or Streamlit
* Add a dashboard for interactive visualization
