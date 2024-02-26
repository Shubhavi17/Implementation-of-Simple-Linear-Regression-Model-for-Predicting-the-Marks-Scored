# Implementation-of-Simple-Linear-Regression-Model-for-Predicting-the-Marks-Scored

## AIM:
To write a program to predict the marks scored by a student using the simple linear regression model.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Jupyter notebook

## Algorithm
```
```
1.Import the standard Libraries.

2.Set variables for assigning dataset values.

3.Import linear regression from sklearn.

4.Assign the points for representing in the graph.

5.Predict the regression for the marks by using the representation of the graph.

6.Compare the graphs and hence we obtained the linear regression for the given datas
```
```


## Program:
```

/*
Program to implement the simple linear regression model for predicting the marks scored.
Developed by: Shubhavi.M
RegisterNumber: 212223040199

*/

import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
plt.scatter(df['X'],df['Y'])
plt.xlabel('X')
plt.ylabel('Y')
X=df.iloc[:,0:1]
Y=df.iloc[:,-1]
X
from sklearn.model_selection import train_test_split
X_train,X_test,Y_train,Y_test=train_test_split(X,Y,test_size=0.2,random_state=0)
from sklearn.linear_model import LinearRegression
lr=LinearRegression()
lr.fit(X_train,Y_train)
X_train
Y_train
lr.predict(X_test.iloc[0].values.reshape(1,1))
plt.scatter(df['X'],df['Y'])
plt.xlabel('X')
plt.ylabel('Y')
plt.plot(X_train,lr.predict(X_train),color='red')
m=lr.coef_
m[0]
b=lr.intercept_
b
```


## Output:
![Screenshot 2024-02-26 163008](https://github.com/Shubhavi17/Implementation-of-Simple-Linear-Regression-Model-for-Predicting-the-Marks-Scored/assets/150005085/e9ca64bc-a840-4c76-b31c-02adbf3f43c4)
![Screenshot 2024-02-26 163939](https://github.com/Shubhavi17/Implementation-of-Simple-Linear-Regression-Model-for-Predicting-the-Marks-Scored/assets/150005085/2c6d688d-e686-40dc-8896-d4c87327041d)
![Screenshot 2024-02-26 164049](https://github.com/Shubhavi17/Implementation-of-Simple-Linear-Regression-Model-for-Predicting-the-Marks-Scored/assets/150005085/c6d5db68-b436-4dc7-aeb5-61d536c6414b)
![Screenshot 2024-02-26 164116](https://github.com/Shubhavi17/Implementation-of-Simple-Linear-Regression-Model-for-Predicting-the-Marks-Scored/assets/150005085/a0ebf571-196b-4f68-babd-e148056c52c1)
![Screenshot 2024-02-26 164234](https://github.com/Shubhavi17/Implementation-of-Simple-Linear-Regression-Model-for-Predicting-the-Marks-Scored/assets/150005085/7707386d-416c-436a-8806-b2017b917400)
![Screenshot 2024-02-26 164302](https://github.com/Shubhavi17/Implementation-of-Simple-Linear-Regression-Model-for-Predicting-the-Marks-Scored/assets/150005085/22e5ba72-4e85-4e78-8a83-00ea4b4e5496)
![Screenshot 2024-02-26 164320](https://github.com/Shubhavi17/Implementation-of-Simple-Linear-Regression-Model-for-Predicting-the-Marks-Scored/assets/150005085/5c62bd52-09f3-41af-bf67-0e9bc3ff057b)




## Result:
Thus the program to implement the simple linear regression model for predicting the marks scored is written and verified using python programming.
