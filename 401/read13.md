# Linear Regression


![](linear-regression-in-machine-learning.png)
Linear regression is a supervised learining algorithm used when target / dependent variable continues real number. It establishes relationship between dependent variable  y  and one or more independent variable  x  using best fit line. It work on the principle of ordinary least square  (OLS)  / Mean square errror  (MSE) . In statistics ols is method to estimated unkown parameter of linear regression function, it's goal is to minimize sum of square difference between observed dependent variable in the given data set and those predicted by linear regression fuction.

the ***dependent variable*** is denoted Y and the independent variable is denoted X.


***independent (or predictor)*** variable and one continuous dependent (or outcome) variable



```
import pandas  as pd #Data manipulation
import numpy as np #Data manipulation
import matplotlib.pyplot as plt # Visualization
import seaborn as sns #Visualization
```


# Import dataset
```
df = pd.read_csv(path+'something.csv')
#Lets look into top few rows and columns in the dataset
df.head()
```
# split data set into training and test 

```
# Import the dataset
dataset = pandas.read_csv('salaryData.csv')
x = dataset.iloc[:, :-1].values
y = dataset.iloc[:, 1].values

# Split the dataset into the training set and test set
# We're splitting the data in 1/3, so out of 30 rows, 20 rows will go into the training set,
# and 10 rows will go into the testing set.
xTrain, xTest, yTrain, yTest = train_test_split(x, y, test_size = 1/3, random_state = 0)
```


# train 

```
linearRegressor = LinearRegression()

linearRegressor.fit(xTrain, yTrain)
```

# Test

```

yPrediction = linearRegressor.predict(xTest)

```