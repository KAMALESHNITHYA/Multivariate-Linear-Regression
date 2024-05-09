# Implementation of Multivariate Linear Regression
## Aim
To write a python program to implement multivariate linear regression and predict the output.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1
Import pandas as pd and from sklearn import linear_model

### Step2
Read the csv file from the drive

### Step3
Drive the required list from the file

### Step4
Print the list of the program

### Step5
End the program

## Program:
```
#Python program to implement multivariate linear regression and predict the output.
#Developed by: KAMALESH R
#Register Number: 212223230094

import pandas as pd
from sklearn import linear_model

df=pd.read_csv("cars.csv")
a=df[['Weight','Volume']]
b=df[['CO2']]
regr=linear_model.LinearRegression()
regr.fit(a,b)
print("coefficient",regr.coef_)
print("Intercept:",regr.intercept_)
print("Amount:",regr.predict([[3300,1300]]))






```
## Output:
![image](https://github.com/KAMALESHNITHYA/Multivariate-Linear-Regression/assets/145743119/4b28aa3c-6ec7-4a4d-8d36-865d477207b0)
![Screenshot 2024-05-09 134803](https://github.com/KAMALESHNITHYA/Multivariate-Linear-Regression/assets/145743119/bb03642c-3dc9-47e6-b2ee-e9291962c440)

### Insert your output

<br>

## Result
Thus the multivariate linear regression is implemented and predicted the output using python program.
