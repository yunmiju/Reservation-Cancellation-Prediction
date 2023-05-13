# Hotel Reservation Cancellation Prediction

Dataset is retrieved from <img width="50" alt="kaggle" src="https://github.com/yunmiju/ReservationCancellationPrediction/assets/80064255/b3a0e156-ca5e-4148-bd21-0b7f7dbaa731">

[Reservation Cancellation Prediction Dataset](https://www.kaggle.com/datasets/gauravduttakiit/reservation-cancellation-prediction?select=train__dataset.csv)


## About

The advent of online hotel booking platforms has dramatically revolutionized customer behavior and booking possibilities. However, this comes with a significant downside - a high rate of cancellations and no-shows. Factors such as scheduling conflicts or changes in plans often lead to these cancellations. In many cases, the ease and low cost or even no cost of cancellation, while advantageous for hotel guests, are less desirable for hotel operators, potentially leading to revenue loss.

This project is aimed at addressing this challenge. As a Data Scientist, the goal is to construct a machine learning model that assists hotel proprietors in gaining a better understanding of their customers' booking behaviors. Specifically, the model is designed to predict whether a customer will honor a reservation or cancel it.

I use the Reservation Cancellation Prediction Dataset from Kaggle, containing approximately 18,000 instances with 18 attributes, including the target column "booking_status".

The primary objective is to create an accurate binary classification model to predict 'booking_status', a binary variable that indicates if a reservation has been cancelled (1 = cancelled) or not (0 = not cancelled).

In this relatively small dataset, all 18 features are numeric or numerically encoded categorical variables. For example, 'room_type_reserved' appears to be a binary encoded feature. During data preparation, I will explore the feature types and address potential scaling issues.

This project applies machine learning techniques to make predictive decisions, ultimately enabling hotel owners to better understand reservation cancellation patterns and adjust their strategies accordingly.


## Setting

Please download env.yml then create envioronment by 'conda env create -f env.yml'

Run the project on the env.


## Libraries

- sklearn
- pandas
- numpy
- matplotlib
- seaborn
- xgboost
- scipy
- shap


## Models/Algorithms

- Dummy Classifier
- Logistic Regression
- LightGBM
- XGBOOST
- Random Forest



