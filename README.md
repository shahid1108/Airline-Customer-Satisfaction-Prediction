# ✈️ Airline Customer Satisfaction Prediction  

## Project  Overview
This machine learning project predicts airline customer satisfaction based on various factors like flight experience, service quality, and passenger feedback. Using Python and key ML libraries, the model classifies customers as **Satisfied** or **Dissatisfied**, helping airlines improve their services.  

## Dataset
1. **Source**: Kaggle or any airline customer satisfaction dataset
2. **Features**: - Passenger details (e.g., Age, Gender, Customer type, Class, Flight Distance) - Flight experience (e.g., Seat comfort, On-board service, In-flight entertainment, Checking Service)
       - Flight details (e.g., Departure delay, Arrival delay)
3. **Target Variable**: Satisfaction

## Approach & Methodology
1. **Data Preprocessing**:
  - Handling missing values
  - Encoding categorical variables
  - Feature scaling
2. **Exploratory Data Analysis (EDA)**:
- Data visualization
- Correlation analysis
3. **Model Building**:
- Train-test split
- Trying different ML models

## Technologies Used  
- **Pandas, Numpy** –Data importing, Data processing, Filing the null values etc.
- **Matplotlib, Seaborn** – Data visualization, Creating Charts
- **ML Algorithms**: Dicision Tree, Random Forest,SVM

##  Key Features  
- Data preprocessing and feature engineering  
- Exploratory Data Analysis (EDA)  
- Model training, evaluation, and optimization  
- Insights into factors influencing satisfaction  
- Create a bar chart for Customers who are satisfied or not
- Dropped the bull values
- Dropeeds a column which is unuseful.
- Splited the data into testing and training
- Applied StandardScaler for  Scaling the data.
- Applied LabelEncoding to convert the DataType


##  Results  
- Identifies key factors affecting customer experience  
- Achieves high accuracy using optimized ML models  
- Provides actionable insights for airline service improvements.
- Applied 5 ML Models For the beat accuracy and got a beat accuracy  with RandomForestClasifier 96.12%.
- Also Applied LinearRegression,SVC,DicisionTreeClassifier, KNeighborsClassifier.
- Most of People Are Satisfied with this airline and also the most number of count is females.


## Project Outcomes
1. **Accurate Prediction of Customer Satisfaction**
       – The best-performing model achieved an accuracy of 96.12%, effectively distinguishing satisfied and dissatisfied customers.

2. **Key Factors Influencing Satisfaction Identified**
       – Features like flight delay, seat comfort, in-flight entertainment, and customer service had the highest impact on satisfaction.

3. **Improved Data Insights Through EDA**
       – Visualizations revealed trends in customer preferences, common dissatisfaction reasons, and correlations between flight experience and ratings.

4. **Comparison of Machine Learning Models**
       – Evaluated multiple algorithms, such as Logistic Regression, Random Forest,DIcision Tree and SVM, to determine the most effective model.

