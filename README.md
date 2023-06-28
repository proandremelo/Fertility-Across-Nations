# Fertility Rate Prediction Model
  This repository contains a machine learning model that predicts the fertility rate of countries based on historical data.
  The model was created using a table of countries' fertility indexes that has columns for each year from 1960 to 2022,
as well as columns for the country name and code.
# Methodology
  The model was created using a regression approach, which involves training a model to predict a continuous output variable
(in this case, the fertility rate) based on one or more input variables (in this case, the historical fertility indexes for
each country). The model was trained using a pipeline that included imputation of missing values.
# Data Sources
  The data used to train the model was obtained from the Kaggle Dataset https://www.kaggle.com/datasets/omarsobhy14/fertility-rate-per-country
# Results
The model achieved a mean absolute percentage error (MAPE) of 2.37 on the test set, indicating that it is able to predict the
fertility rate of countries with reasonable accuracy.
# Future Work
In the future, the model could be improved by incorporating additional features such as economic indicators, social factors,
and demographic trends.
