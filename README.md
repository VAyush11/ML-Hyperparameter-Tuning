Hey there! I recently learnt about what hyperparameters of machine learning models are, and how we can tune them to further increase our predictive models' accuracies/performance. So in this repository, I'm sharing the code I used to create, train, and finally tune 5 of the most commonly used classification models in machine learning. These are:

1) Logistic Regression
2) Classification Trees
3) Random Forests
4) Xtreme Gradient Booster (XGBoost)
5) Neural Network (A basic multi-layer perceptron)

I've made use of the RandomisedSearchCV optimisation technique, as I did not have prior knowledge about what are some of the 'common' variable values that people usually test for in a GridSearchCV optimisation. I've opted to tune between 2-5 hyperparameters simultaneously for each model, but you can feel free to start by tuning just one, and taking it from there (For instance, the max_depth in a decision tree, or n_trees in a random forest)

As the dataset is very basic, the improvement in model accuracy before and after optimisation may not be too significant. However, this same technique are directly applicable to models being trained on larger, more complex datasets. 

I used these sources to learn more about RandomisedSearchCV and to know which parameters to tune. Hopefully these combined with my code will provide a useful starting point! :)
1) https://machinelearningmastery.com/hyperparameter-optimization-with-random-search-and-grid-search/
2) https://machinelearningmastery.com/hyperparameters-for-classification-machine-learning-algorithms/

Glhf! 
