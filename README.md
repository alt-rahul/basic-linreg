# Introduction

Intially this was just going to be project on making a linear model in PyTorch, but now I've decided this is going to be a monorepo of a collection of linear models (regression) - including the ones from scikit-learn. 


* `train.ipynb` ~ training L1 Linear torch model on non-cyclical unemployment
* `other_lin.ipynb` ~ exploring different kinds of regression and metrics to assess it
* `diabetes.csv` ~ diabetes dataset found on Kaggle


## Modeling Unemployment

### About
I used the FRED database to pull historical data of noncyclical unempolyment to create a basic linear regression model using pytorch.


### The Jounrey 
It was actually pretty interesting because this the only the second time I'm using `PyTorch`, so there was defintely some ups and downs during this project.

Initally what I *attempted* to do was train x-values on x-values. But after realizing this mistake, I had to make the **dates** as my independent variable or my `X_train` & `X_test` and the actually **unemployment rates** as my dependent variable or `y_train` & `y_test`. 

Maybe a little bit later (after I actually know what I'm doing), I'll model future unemployment rates based on previous values instead of dates with some type of activation function. 


![alt text](image-1.png)

---

### Replicate It

It's easy to replicate this project. All you have to do is fork this repository and replace `api_key=api_key` with your actual api key from FRED database. 

Have fun. 