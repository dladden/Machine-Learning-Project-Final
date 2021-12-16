# Machine Learning Naïve Bayes Project Final

## By Denys Ladden and Emil B. Berglund


### Uses supervised learning method
Uses supervised learning method <br />
Output variable is categorical (since it is a classification technique) <br />
Types of Different NB versions are tested for acccuracy <br />
 <br /> 
Overview:
 <br /> 
  Gaussian 
Continuous variables, assumes normal distribution. Example, our dataset.
Multinomial Preferred when data is distributed multinomially. Constant p, unrelated repeated trials, discrete number of outcomes. Example, text classification.
Bernoulli This one requires values to be binary valued, meaning they need to be categorical, for this one, dummy variables would be necessary in our dataset. Example, 10 coin tosses.
<p align="center">
  <img src="https://i.ibb.co/NL9D2Dq/Picture1" />
</p>




### Data sources:
 <br /> 
The database name: Iris Flower Dataset<br /> 
The source of our dataset:<br /> 
https://www.kaggle.com/arshid/iris-flower-dataset<br /> 

Output variable, categorical: <br /> 
Iris-subspecies<br /> 

There are 4 predictor variables, all numerical:<br /> 
Sepal length<br /> 
Sepal width<br /> 
Petal length<br /> 
Petal width<br /> 
GaussianNB model for our case<br /> 

 <br /> 







### Models details: <br /> 

 <br /> 
 <p align="center">
  <img src="https://i.ibb.co/qWcrcBN/Picture2.png" />
</p>
 
Here we can see the best model is the gaussian, and that makes sense since our dataset contains continuous variables. Since multinomial does categorical values, but since the input variables were continuous it converted the to categorical by classifying them into ranges.
The Bernoulli did the same thing as multinomial, however, it only classified into two categories, so it was way less accurate than the multinomial.
