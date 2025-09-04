This folder contains all of the neccesary code to obtain the results that I presented in my report.

To run any of the following files, ensure that the repoistory that contains all code relevent to the MNIST Fashion dataset is in a folder named "repo" and that all neccesary libraries are downloaded.

This folder contains five ipynb files. The files and a short description of the work they contain is as follows:

part_one.ipynb: Contains all scripts to preprocess, build, train and test the various linear support vector machine models presented in my assingment.
I began with preprocessing the data (which is done the same way in each of the first four files).
The code then builds various models and graphs the results, some include k-fold cross-validation, which is implemented based off of my approach from assingment 1.

part_two.ipynb: Follows the same structure of part_one.ipynb, first preprocess the data, trains the models (some with k-fold cross-validation) and graphs the results.

part_three.ipynb: Follows the same structure as part_one.ipynb, first preprocess the data, trains the models (some with k-fold cross-validation) and graphs the results.

part_four.ipynb: Preprocesses the data, then trains three models (SVM with linear kernel, SVM with Gaussian kernel, Neural Network) based off of the optimal hyperparameters discovered in the previous files. 

bonus.ipynb: Preprocesses the data and makes small training and validation sets.
Tunes y, C, m, and r to find optimal combination, then trains a model with this combination of hyperparameters and computes test error.
Builds a model with no augmented data to form a baseline
Tunes hyperparameters y, c and m while r is fixed, trains model on these parameters and compute test error.
Tunes hyperparameters y, c and r while m is fixed, trains model on these parameters and compute test error.


The following resources were used to help write components of code:
-https://scikit-learn.org/stable/modules/svm.html
-https://www.datacamp.com/tutorial/svm-classification-scikit-learn-python
As well as further scikit learn documentation