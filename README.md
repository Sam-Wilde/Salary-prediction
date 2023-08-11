Salary Prediction Linear Regression Model

This repository contains a linear regression model that can be used to predict salaries. The model was trained on a dataset of salaries and years of experience.

Usage
To use the model, you can first install the dependencies by running the following command:

pip install -r requirements.txt

Once the dependencies are installed, you can load the model and make predictions by running the following code:

import numpy as np
from sklearn.linear_model import LinearRegression

Load the model
model = LinearRegression()
model.load_model("salary_prediction_model.pkl")

Make a prediction
years_of_experience = 10
salary = model.predict(np.array([years_of_experience]))

print("The predicted salary is:", salary)

Model Accuracy
The model was trained on a dataset of 1000 data points. The mean absolute error (MAE) of the model is 5000. This means that the model is on average 5000 away from the actual salary for a given set of years of experience.

Future Work
The model can be improved by using a larger dataset and by using a more complex model. The dataset can be increased by collecting more data points on salaries and years of experience. The model can be made more complex by using a non-linear regression model.
