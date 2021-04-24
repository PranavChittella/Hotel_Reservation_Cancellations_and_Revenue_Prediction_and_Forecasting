# Hotel_Reservation_Cancellations_and_Revenue_Prediction_and_Forecasting
##Predicting the bookings that might get cancelled and also forecasting the ADR , which shows the revenue that the company can generate using Time Series Forecasting and Deep Learning

Insight about the Data:
This data article describes two datasets with hotel demand data. One of the hotels (H1) is a resort hotel and the other is a city hotel (H2). Both datasets share the same structure, with 31 variables describing the 40,060 observations of H1 and 79,330 observations of H2. Each observation represents a hotel booking.
Data Source: https://www.sciencedirect.com/science/article/pii/S2352340918315191#bib5 

Problem Statement:
The data points us to various segments of Machine Learning with many variables, hence I have chosen it perform classification for predicting the cancellations of the bookings made.Also, as an extension we are predicting the ADR as a time-series variable.
ADR (Average Daily Rate) is defined Calculated by dividing the sum of all lodging transactions by the total number of staying nights.

ClassificationHotelProblem.ipynb Notebook consists of the classification activity performed on the "IsCancelled" feature. Data Analysis and the algorithms (XGBoost,LightGBM,CatBoost) and a tailor-made Stacker Algorithm is shown through interactive comments. Additionaly , a deep Neural Network is applied as well. The models are saved for deployment with StreamLit.
