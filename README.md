# Decision_Tree_Classifier_using_Ecoli_Dataset

In this notebook, we will train two decision tree classifiers and compare their performance.

The data file and a brief description file of an E Coli bacteria dataset are available in a web repository managed by
the UCI (University of California at Irvine) Centre for Machine Learning and Intelligent Systems. See https://archive.ics.uci.edu/ml/datasets/ecoli
The spreadsheet data is in the ecoli.data file and description about the data is in the ecoli.names file.

The tasks done in this notebook are as follows.
1. Reading in the ecoli.data file, providing a plot for data visualisation. Removing those classes having less than 10 instances as it is not
   possible to classify them. Dealing with non-numerical data. 
2. Implementing two Decision Tree classifiers, one being trained on the raw (unscaled) features and another on the scaled features computed by StandardScaler.
   For each classifier, using grid search with 3-fold cross validation on the 'criterion', 'max_depth', 'min_samples_leaf', and 'max_features' hyperparameters (with three values for each).
3. Comparing the average F1-scores of our two classifiers from the 3-fold cross validation and displaying their confusion matrices.
