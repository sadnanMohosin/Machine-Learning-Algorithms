## Logistic Regression
Logistic regression is a supervised learning algorithm used to predict a dependent categorical target variable. In essence, if you have a large set of data that you want to categorize, logistic regression may be able to help. 

## Types of Logistic Regression
* Binary logistic regression: animal or not an animal—it’s an either/or solution. There are just two possible outcome answers. This concept is typically represented as a 0 or a 1 in coding.
* Multinomial logistic regression: Multinomial logistic regression is a model where there are multiple classes that an item can be classified as. There is a set of three or more predefined classes set up prior to running the model. Examples include:

    * Classifying texts into what language they come from.
    * Predicting whether a student will go to college, trade school or into the workforce.
    * Does your cat prefer wet food, dry food or human food?
* Ordinal logistic regression : Ordinal logistic regression is also a model where there are multiple classes that an item can be classified as; however, in this case an ordering of classes is required. Classes do not need to be proportionate. The distance between each class can vary. Examples include:

    * Ranking restaurants on a scale of 0 to 5 stars.
    * Predicting the podium results of an Olympic event.
    * Assessing a choice of candidates, specifically in places that institute ranked-choice voting.

## Linear Regression vs Logistic Regression
**Linear Regression** is a machine learning algorithm based on supervised regression algorithm. Regression models a target prediction value based on independent variables. It is mostly used for finding out the relationship between variables and forecasting. Different regression models differ based on – the kind of relationship between the dependent and independent variables, they are considering and the number of independent variables being used.

**Logistic regression** is basically a supervised classification algorithm. In a classification problem, the target variable(or output), y, can take only discrete values for a given set of features(or inputs), X.

## When to use logistic regression
Logistic regression is applied to predict the categorical dependent variable. In other words, it's used when the prediction is categorical, for example, yes or no, true or false, 0 or 1. The predicted probability or output of logistic regression can be either one of them, and there's no middle ground.

In the case of predictor variables, they can be part of any of the following categories:

* Continuous data: Data that can be measured on an infinite scale. It can take any value between two numbers. Examples are weight in pounds or temperature in Fahrenheit.
* Discrete, nominal data: Data that fits into named categories. A quick example is hair color: blond,  black, or brown.
* Discrete, ordinal data: Data that fits into some form of order on a scale. An example is telling how satisfied you're with a product or service on a scale of one to five.
Logistic regression analysis is valuable for predicting the likelihood of an event. It helps determine the probabilities between any two classes.

In a nutshell, by looking at historical data, logistic regression can predict whether:

* An email is a spam
* It’ll rain today
* A tumor is fatal
* An individual will purchase a car
* An online transaction is fraudulent
* A contestant will win an election
* A group of users will buy a product
* An insurance policyholder will expire before the policy term expires
* A promotional email receiver is a responder or non-responder

In essence, logistic regression helps solve probability and classification problems. In other words, you can expect only classification and probability outcomes from logistic regression.

For example, it can be used to determine the probability of something being “true or false” and also for deciding between two outcomes like “yes or no”.

**A logistic regression model can also help classify data for extract, transform, and load (ETL) operations. Logistic regression shouldn't be used if the number of observations is less than the number of features. Otherwise, it may lead to overfitting.**