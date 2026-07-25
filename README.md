# SGD-Regressor-for-Multivariate-Linear-Regression
# Developed by: VIGNESHWARAN.P
# RegisterNumber:  212224040358
## AIM:
To write a program to predict the price of the house and number of occupants in the house with SGD regressor.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Jupyter notebook

## Algorithm
~~~
1. Import the required Python libraries and create the house dataset.
2.Separate the input features and output values (house price and number of occupants).
3.Train the SGD Regressor model using the training data.
4.Predict the house price and number of occupants using the trained model.
5.Display the predicted results and evaluate the model performance.
~~~

## Program:
```

The following Program to implement the multivariate linear regression model for predicting the price of the house and number of occupants in the house with SGD regressor.

from sklearn.preprocessing import StandardScaler

scaler = StandardScaler()
X_scaled = scaler.fit_transform(X)

model.fit(X_scaled, y)

new_house = [[1600, 3]]
new_house_scaled = scaler.transform(new_house)

prediction = model.predict(new_house_scaled)

print("Predicted House Price (Lakhs):", round(prediction[0][0], 2))
print("Predicted Number of Occupants:", round(prediction[0][1]))
```

## Output:

<img width="431" height="64" alt="image" src="https://github.com/user-attachments/assets/9095d2f6-1a30-4242-be18-fa4610445d63" />



## Result:
Thus the program to implement the multivariate linear regression model for predicting the price of the house and number of occupants in the house with SGD regressor is written and verified using python programming.
