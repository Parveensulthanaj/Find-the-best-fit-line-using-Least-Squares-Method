# Implementation of Univariate Linear Regression
## AIM:
To implement univariate Linear Regression to fit a straight line using least squares.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Jupyter notebook

## Algorithm
1. Get the independent variable X and dependent variable Y.
2. Calculate the mean of the X -values and the mean of the Y -values.
3. Find the slope m of the line of best fit using the formula. 
<img width="231" alt="image" src="https://user-images.githubusercontent.com/93026020/192078527-b3b5ee3e-992f-46c4-865b-3b7ce4ac54ad.png">
4. Compute the y -intercept of the line by using the formula:
<img width="148" alt="image" src="https://user-images.githubusercontent.com/93026020/192078545-79d70b90-7e9d-4b85-9f8b-9d7548a4c5a4.png">
5. Use the slope m and the y -intercept to form the equation of the line.
6. Obtain the straight line equation Y=mX+b and plot the scatterplot.

## Program:
```
Name:PARVEEN SULTHANA J
RegisterNumber: 212224040233
```
```
import matplotlib.pyplot as plt
import numpy as np
x=np.array([1,2,3,7,6,35.5,45,22,54])
y=np.array([5,8,6,24,7,11,15,18,20])
lr=1.53*x+2.88
print(f"x values: {x}")
print(f"y values: {y}")
plt.scatter(x,y,color='green')
plt.plot(x,lr,color='red')
plt.xlabel('X VALUES')
plt.ylabel('Y VALUES')
plt.title('LINEAR REGRESSION')
plt.show()
```
## Output:
<img width="758" height="593" alt="ML01" src="https://github.com/user-attachments/assets/4e8ec12c-00b1-40cb-911e-e46b956e09b5" />



## Result:
Thus the univariate Linear Regression was implemented to fit a straight line using least squares using python programming.
