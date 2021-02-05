### Tree

First, select one of the datasets from section 10.14 of the test(either California Housing or New Zealand Fish) and replicate the analysis, including the plots. You don't have to do the maps. 

Next, select a dataset of your choice and perform a similar analysis. You can perform classification or regresssion, your choice. This should be a more complicated, and if you want, messier, dataset than the ones we've looked at so far. Use the built-in functions that come with the xgboost package to tune the model and optimize your performance, and determine the feature importance.  As this assignment is more focused on using a library, I will be expecting a more thoughtful analysis of the results.

For some more details on XGBoost, you can have a look at : https://arxiv.org/pdf/1603.02754v3.pdf and https://medium.com/@gabrieltseng/gradient-boosting-and-xgboost-c306c1bcfaf5

If you wish to get your hands a bit dirty on tree-related algorithms, there are 2 stretch goals available as well.

Stretch goal #1, 3 points: Implement a basic tree algorithm for both regression and classification. It must work for several loss functions: mean-squared error, misclassification, Gini index, and cross-entropy. You do not have to implement any pruning, but the # of nodes should be a parameter. Select a dataset to test your algorithm on, and tune it using cross-validation to select the optimal # of nodes. Compare against a baseline.

Stretch goal #2, 3 points: Use a simple tree method, (like your tree from stretch goal #1) and implement algorithm 10.3. Select a dataset, tune your algorithm and compare it against a baseline
