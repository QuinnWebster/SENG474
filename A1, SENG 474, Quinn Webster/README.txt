This folder contains all of the neccesary code to obtain the results that I presented in my report.

To run any of the following files, ensure that spambase_augmented.csv is included in the folder and that all neccesary libraries are downloaded.

This folder contains five ipynb files. The files and a short description of the work they contain is as follows:

decision_tree.ipynb: Contains all scripts to build, train and test the various decision trees presented in my assignment. Most scripts follow the same format, I choose one parameter to vary
while keeping all others constant, then graph the various training and testing error for that model. Each section has a markdown header that concisely describes which hyperparameter is being varied in the following code.
To vary the split criterion (Gini Index or Entropy) this can be done at the start of each section.

random_forest.ipynb: Follows the same structure as decision_tree.ipynb, first run each section to train the models, then graph the results.

ada_boost.ipynb: Follows the same structure as decision_tree.ipynb, first run each section to train the models, then graph the results.

k_fold_random_forests.ipynb: Is used to run the code relevent for k-fold cross validation for random forests.
Descibes the ensemble of values that will be tested, and runs a self-implemented k-cross fold validtion on all values of the ensemble.
For each value in the ensemble, it graphs the average error on the validation set.
Once all ensemble values have been run, it chooses the value that resulted in the lowest error and trains a new random forest with that specific value.
It then runs the testing data on that newly trained model to get the final testing error.

k_fold_ada_boost.ipynb: Follows the same structure as k_fold_random_forests.ipynb, but for adaBoost.

The following resources were used to help write components of code:
-https://www.geeksforgeeks.org/building-and-implementing-decision-tree-classifiers-with-scikit-learn-a-comprehensive-guide/
-https://www.geeksforgeeks.org/random-forest-classifier-using-scikit-learn/
As well as scikit learn documentation