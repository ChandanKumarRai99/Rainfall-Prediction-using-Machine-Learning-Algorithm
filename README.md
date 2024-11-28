# Rainfall-Prediction-using-Machine-Learning-Algorithm

## Description: 
This project focuses on predicting rainfall in Sydney using machine learning techniques. It involves analyzing historical weather data to build a predictive model that can classify whether it will rain or not.

## The dataset contains 18 columns:
- Date:The date of observation
- Location:The common name of the location of the weather station
- MinTemp:The minimum temperature in degrees celsius
- MaxTemp:The maximum temperature in degrees celsius
- Rainfall:The amount of rainfall recorded for the day in mm
- Evaporation:The so-called Class A pan evaporation (mm) in the 24 hours to 9am
- Sunshine:The number of hours of bright sunshine in the day
- Humidity 9am:Humidity (percent) at 9am
- Humidity3pm:Humidity (percent) at 3pm
- Pressure 9am:Atmospheric pressure (hpa) reduced to mean sea level at 9am
- Pressure 3pm:Atmospheric pressure (hpa) reduced to mean sea level at 3pm
- Cloud 9 Am:Fraction of sky obscured by cloud at 9am. This is measured in “oktas”, which are a unit of eighths. It records how many eighths of the sky are obscured by clouds. A 0 measure
  indicates completely clear sky whilst an 8 indicates that it is completely overcast.
- Cloud3pm:Fraction of sky obscured by clouds (in "oktas": eighths) at 3pm. See Cload9am for a description of the values.
- Temp 9am:Temperature (degrees C) at 9am
- Temp3pm:Temperature (degrees C) at 3pm
- RainToday:Boolean: 1 if precipitation (mm) in the 24 hours to 9am exceeds 1mm, otherwise 0
- RainTomorrow:Boolean: next day rain

## Key Steps:

### Data Preprocessing:

- Loaded and cleaned the dataset from an Excel file.
- Handled missing values and outliers to ensure data quality.
- Performed feature engineering to extract meaningful insights from raw data

### Exploratory Data Analysis (EDA):

- Analyzed weather patterns and relationships between features using visualizations.
- Identified key variables influencing rainfall, such as humidity, temperature, and wind speed.

### Model Building:

- Built and evaluated multiple machine learning models, including:
- Logistic Regression
- Decision Tree
- Random Forest
- Gradient Boosting (e.g., XGBoost)
- Used techniques like cross-validation and hyperparameter tuning to optimize model performance.

### Evaluation Metrics:
- Assessed model performance using metrics like accuracy, precision, recall, F1-score, and ROC-AUC curve.

### Results and Insights:

- The final model demonstrated high accuracy in predicting rainfall.
- Identified significant features contributing to rainfall predictions.

### Tools and Libraries Used:

- Languages: Python
- Libraries: Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, XGBoost
- Platform: Jupyter Notebook

This project highlights the application of machine learning to solve a real-world problem, showcasing the power of data-driven predictions for weather forecasting.

