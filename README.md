# Modeling Unemployment

### About
I used the FRED database to pull historical data of noncyclical unempolyment to create a basic linear regression model using pytorch.


### The Jounrey 
It was actually pretty interesting because this the only the second time I'm using `PyTorch`, so there was defintely some ups and downs during this project.

Initally what I *attempted* to do was train x-values on x-values. But after realizing this mistake, I had to make the **dates** as my independent variable or my `X_train` & `X_test` and the actually **unemployment rates** as my dependent variable or `y_train` & `y_test`. 

Maybe a little bit later (after I actually know what I'm doing), I model future unemployment rates based on previous values instead of dates with a some type of activation function. 

---

### Replicate It

It's easy to replicate this project. All you have to do is fork this repository and replace `api_key=api_key` with your actual api key from FRED database. 

Have fun. 