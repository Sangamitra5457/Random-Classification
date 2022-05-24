# RANDOM CLASSIFICATION
## AIM:
To write a python program to perform random classification.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Google Colab /Jupiter Notebook

## Related Theoritical Concept:

## Algorithm
1.In Random Forest n number of random records are taken from the data set having
k number of records.
2.Individual decision trees are constructed for each sample.
3.Each decision tree will generate an output.
4.Final output is considered based on Majority Voting or Averaging for Classification
and regression respectively

## Program:
```
/*
Program to implement random classification.
Developed by   :Sangamitra SD
RegisterNumber :  212219040134
import matplotlib.pyplot as plt
from sklearn import datasets
X,y = datasets.make_blobs(n_samples=100,n_features=2,
centers=2,cluster_std=1.05,random_state=2)
fig=plt.figure(figsize=(10,8))
plt.plot(X[:,0][y==0], X[:,1][y==0],'pc')
plt.plot(X[:,0][y==1], X[:,1][y==1],'bo')
plt.xlabel("Feature 1")
plt.ylabel("Feaure 2")
plt.title("Random Classification Data with 2 classes")
/*
```

## Output:
![image](https://user-images.githubusercontent.com/106137647/169959933-85e85901-e541-453b-a514-efb0e391cef2.png)



## Result:
Thus, the random classifier was successfully implemented using python 
programming
