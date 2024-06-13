# MultilinearRegression
In Multilinear Regression the will be a dataset of multiple independent variable and a dependent variable.
So based on multiple independent variable we will predict the best result we get.
In this case there are 5 columns 
1.R&D Spend
2.Administration
3.Marketing Spend
4.State
5.Profit

* Fistly,we have to import all the liberaries required like numpy,pandas,matplotlib etc. and columnTransformer,OneHotEncoder,train_test_split etc from sklearn library.
* Then,we will import the dataset='50_Startups.csv'.
* Now, in these 5 columns the 4rth one State consists for Alphabetic words ,so we have to change this column into a numeric one through a method of encoding categorical data.
* Then we have to split the dataset into the training set and test set.
* After that do the training of the linear regression model just like in simple linear regression because there is only one difference in the multi linear and simple linear which is no. of independent variable.
* So after doing the training , now predict the test results
* For predicting, make 2 vectors and print them vertically.
