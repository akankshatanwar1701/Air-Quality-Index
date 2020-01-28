# Air-Quality-Index :rocket:

## Uses Linear Multivariate Regression 
We have hypothetical air samples of different locations with extracted five features of the air collected which can be used to predict the air quality index.

**Libraries used:** numpy,pandas,matplotlib

**Variables used:** 
1. x: Training data without y labels
2. y: Labels for the training data
3. u: numpy array contaning mean value for each feature
4. std: numpy array containing standard deviation for each feature
5. X: Normalised x
6. theta: numpy array with the values of theta from theta(0) to theta(n-1) no. of values being equivalent to number of features
7. error_list: error after each iteration/epoch
8. T: Testing data
9. y_: numpy array having all the labels for T or labels for the testing data

**Gist and context:** 
 * We are training our model on the previously provided hypothetical data, using **linear multivariate regression** i.e taking in account      multiple features to find the best plane which passes through all the training data points. 
 
