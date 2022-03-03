## Brief Introduction to Decision Trees
A decision tree is a supervised machine learning algorithm that can be used for both classification and regression problems. A decision tree is simply a series of sequential decisions made to reach a specific result. Here’s an illustration of a decision tree in action (using our above example):

![](https://cdn.analyticsvidhya.com/wp-content/uploads/2020/05/rfc_vs_dt11.png)

Let’s understand how this tree works.

First, it checks if the customer has a good credit history. Based on that, it classifies the customer into two groups, i.e., customers with good credit history and customers with bad credit history. Then, it checks the income of the customer and again classifies him/her into two groups. Finally, it checks the loan amount requested by the customer. Based on the outcomes from checking these three features, the decision tree decides if the customer’s loan should be approved or not.

The features/attributes and conditions can change based on the data and complexity of the problem but the overall idea remains the same. So, a decision tree makes a series of decisions based on a set of features/attributes present in the data, which in this case were credit history, income, and loan amount.

Now, you might be wondering:

Why did the decision tree check the credit score first and not the income?

This is known as feature importance and the sequence of attributes to be checked is decided on the basis of criteria like Gini Impurity Index or Information Gain. The explanation of these concepts is outside the scope of our article here but you can refer to either of the below resources to learn all about decision trees:

[Tree-Based Algorithms: A Complete Tutorial from Scratch (in R & Python)](https://www.analyticsvidhya.com/blog/2016/04/tree-based-algorithms-complete-tutorial-scratch-in-python/?utm_source=blog&utm_medium=decision-tree-vs-random-forest-algorithm)

## An Overview of Random Forest
Random Forest is a tree-based machine learning algorithm that leverages the power of multiple decision trees for making decisions. As the name suggests, it is a “forest” of trees!

But why do we call it a “random” forest? That’s because it is a forest of randomly created decision trees. Each node in the decision tree works on a random subset of features to calculate the output. The random forest then combines the output of individual decision trees to generate the final output.

In simple words:

The Random Forest Algorithm combines the output of multiple (randomly created) Decision Trees to generate the final output.

![](https://cdn.analyticsvidhya.com/wp-content/uploads/2020/02/rfc_vs_dt1.png)

## Why Did Random Forest Model Outperform the Decision Tree?

![](https://cdn.analyticsvidhya.com/wp-content/uploads/2020/05/rfc_vs_dt19.png)

As you can clearly see in the above graph, the decision tree model gives high importance to a particular set of features. But the random forest chooses features randomly during the training process. Therefore, it does not depend highly on any specific set of features. This is a special characteristic of random forest over bagging trees. You can read more about the bagging trees classifier [here](https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.BaggingClassifier.html#sklearn.ensemble.BaggingClassifier).

Therefore, the random forest can generalize over the data in a better way. This randomized feature selection makes random forest much more accurate than a decision tree.

## Which One Should We Choose – Decision Tree or Random Forest?

Random Forest is suitable for situations when we have a large dataset, and interpretability is not a major concern.

Decision trees are much easier to interpret and understand. Since a random forest combines multiple decision trees, it becomes more difficult to interpret. Here’s the good news – it’s not impossible to interpret a random forest. Here is an article that talks about interpreting results from a random forest model:

* [Decoding the Black Box: An Important Introduction to Interpretable Machine Learning Models in Python.](https://www.analyticsvidhya.com/blog/2019/08/decoding-black-box-step-by-step-guide-interpretable-machine-learning-models-python/?utm_source=blog&utm_medium=decision-tree-vs-random-forest-algorithm)

Also, Random Forest has a higher training time than a single decision tree. You should take this into consideration because as we increase the number of trees in a random forest, the time taken to train each of them also increases. That can often be crucial when you’re working with a tight deadline in a machine learning project.

But I will say this – despite instability and dependency on a particular set of features, decision trees are really helpful because they are easier to interpret and faster to train. Anyone with very little knowledge of data science can also use decision trees to make quick data-driven decisions.
