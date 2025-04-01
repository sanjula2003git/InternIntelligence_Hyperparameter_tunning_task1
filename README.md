# InternIntelligence_Hyperparameter_tunning_task1
Hyperparameter Tuning is the process of optimizating the hyperparameters of machine learning model to improve its performance.Hyperparameters are settings that are not learnt from data but are set before training such as learning rate,batch size and many more.

# Why is Hyperparameter Tuning is important?
1.Improves model performance:
Finding the right combination of parameters can increase the overall performance of the machine learning model.
2.Prevents overfitting and underfitting:
Proper tuning helps balance bias and variance ,ensuring model generalises well to new data.
3.Optimizes Training Time:
Poorly chosen hyperparameters can take more time for training.
4.Enhances model stability:
Good hyperparameter selection can prevent training issues like overfitting/underfitting issues.

# Common Hyperparameter-Tuning Methods:
1.Grid search:
Tries all combination of predefined set of values.
2.Random search:
Samples random combination of hyperparameters , better choice than grid search.
3.Bayesian optimization:
Uses probablity models to find best hyperparameters based on past evaluations.

# What I did here?
1.I imported all libraries i need(Optuna,numpy,pandas,scikit)
2.I loaded the iris dataset which contains specific details like petal length,stem length of flowers that belong to iris species.
3.I converted that dataset into pandas dataframe.
4.I listed some hyperparameters for randomforest(which is the machine learning model we are going to use here , and the parameters may vary for every model).
5.first parameter is n_estimators , it controls the number of decision trees in the randomforest classifier. and the range i chose for this parameter is 50 to 300 with step 50.
6.second parameter is max_depth , controls how depth a tree can grow. The range i have chosen is 3 to 20.
7.third parameter is min_samples_split,controls how many samples are need to split a node in a tree.The range i have chosen is 2 to 10.
8.fourth parameter is max_feature , controls how many features a tree considers before splitting . The features i have chosen is sqrt,log2,none.
9.Then i created the randomforest and passing this parameters .
10.I train the model and evaluate the results at end.







