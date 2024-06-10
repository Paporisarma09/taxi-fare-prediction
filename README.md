# Taxi Fare Prediction

## Taxi Fare Guru: Total Amount Prediction Challenge

### Introduction
This repository contains my work for the Kaggle competition "Taxi Fare Prediction Challenge". The goal of the competition is to predict the fare amount for a taxi ride with various features such as trip distance, passenger count, payment type, and more.

### Dataset Description
This dataset presents an opportunity to construct predictive models aimed at estimating the total amount paid by travelers for taxi journeys. With access to a training set containing the target variable 'total_amount' along with various informative features, participants are challenged to create accurate predictive models.

#### Data Files
The dataset is composed of the following files:
- **train.csv**: The training set, which includes the target variable 'total_amount' and accompanying feature attributes.
- **test.csv**: The test set, containing similar feature attributes but without the target variable 'total_amount,' as it is the variable to be predicted.
- **sample_submission.csv**: A sample submission file provided in the correct format for competition submissions.

#### Columns Description
The dataset comprises various columns, each offering valuable insights into taxi rides. Notably:
- **total_amount**: The total amount paid by the traveler for the taxi ride.
- **VendorID**: An identifier for taxi vendors.
- **tpep_pickup_datetime** and **tpep_dropoff_datetime**: Timestamps indicating pickup and dropoff times.
- **passenger_count**: The number of passengers during the ride.
- **trip_distance**: The distance traveled during the trip.
- **RatecodeID**: Rate code for the ride.
- **store_and_fwd_flag**: A flag indicating whether the trip data was stored and forwarded.
- **PULocationID** and **DOLocationID**: Pickup and dropoff location identifiers.
- **payment_type**: Payment type used for the ride.

Other columns are self-explanatory and contribute to the modeling process. Participants were encouraged to leverage these informative columns to build robust predictive models and contribute to the challenge of predicting the total fare amount accurately.

### Responsibilities
- Conducted Exploratory Data Analysis (EDA) and data preprocessing, including handling missing values, encoding categorical 
  variables, and scaling features.
- Developed and tuned multiple machine learning models:
  - Linear Regression
  - K-Nearest Neighbors (KNN)
  - Decision Tree
  - Random Forest
  - Extra Trees
  - XGBoost
  - Multilayer Perceptron
- Used GridSearchCV for hyperparameter optimization.

### Technologies
- **Programming Languages**: Python
- **Libraries**: Pandas, NumPy, Scikit-learn, XGBoost, Matplotlib, Seaborn.

### Results
- Achieved the highest R² score of 0.914 with the Multilayer Perceptron model.

