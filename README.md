# DM-DecisionTree-sklearn

We will classify and predict heart diseases using decision trees. We can see the
dataset with description in /dataset/heart.csv.
1) Preparing the data: The implementation of decision tree in sklearn package expects digit
encoded categorical data, for example for age data one could have digit 0 for ages from
0 to 10, digit 1 for ages from 11 to 20 and so on. So, you have to convert numerical
features to categories each representing possible value ranges. Then you need to encode
non-numerical values with digits. The dataset has a number of categorical and binary
features that require encoding.
2) Splitting the data: To see how well your classifier performs you need to test it with new
entries. First you need to split your dataset into a training set with 80% of data and a test
set with 20% of data. The training set is used to actually train the classifier and test set is
used to measure it
3) Training and classification: Finally, your decision tree will classify the test dataset. The
Decision Tree in sklearn has various parameters. Try different values for criterion,
max_depth and min_sample_split parameters and train different classifiers. Visualize
each decision tree, test them with the test set and report accuracy for each one.
