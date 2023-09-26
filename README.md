# Logistic-Regression-

Logistic regression is a great model for classification, given that it calculates
the probabilities for an input to be in a certain class. A model that is used when we 
have a binary classification binary ; as in our case, we will use the model to predict
whether this plant is 'iris versicolor' or not 'iris virginica'.

## Dependencies

* pandas 
* numpy
* sklearn
* seaborn
* matplotlib

## Description

### Logistic Regression Formula

$f(x)= \frac {L}{1+ e^{-k(x-x_0)}}$

* f(x)	=	output of the function
* L	=	the curve's maximum value
* k	=	logistic growth rate or steepness of the curve
* x_0	=	the x value of the sigmoid midpoint
* x	=	real number



### Sigmoid Function

The Sigmoid function, an S shaped graph with a given threshold, turns real predicted values into probabilities between 0 and 1. 

 $S(x)= \frac {1}{1+e^{-x}}$

* S(x)	=	sigmoid function
* e	=	Euler's number

### Logistic Loss Function

Logistic Loss is an essential classification metric for evaluating a model, as it quantifies how well
the predicted probabilities align with the actual values.

$−1N∑i=1N[yilogpi+(1−yi)log(1−pi)]$


### Gradient Descent 

Gradient Descent is an optimization algorithm. With a chosen learning 
rate, it alters the parameters to minimize the cost function ; calculating the
partial derivatives of log loss,

* dW = ∂/∂W = W — α * ∂/∂W
* db = ∂/∂b = b — α * ∂/∂b

and alter the coefficients W and b.

* m = m — learning rate * dW
* b = b — learning rate * db
