# WoC
Linear Regression :- 
With the help of gradient descent, the algorithm was implemented. The mean squared error on the training data (cost function) was found to be 1907.0986738107238 and on testing data, the mean squared error was found to be 2841.272510578341.
Initially, I normalized the output values for the training and testing data, which resulted in the involvement of data leakage.

Polynomial Regression :- 
With the help of gradient descent, the algorithm was implemented. The dataset was checked till a polynomial of degree 3. The mean squared error obtained on training sets (cost function) were 62.340740826528695 and 71.69530953845312 for degree 3 and degree 2 repectively. The MSE obtained on testing data were 301675.1939167583 and 301882.2807949841 for degree 3 and degree 2 respectively.
The insanely high values of MSE on testing data indicate overfitting of training data in the model. Hence, regularization might be able to overcome this shortcoming.

Logistic Regression :- 
With the help of gradient descent and one vs all classifier, the algorithm was implemented. The cost function i.e. Binary Cross Entropy was found to be equal to 2.0561311357222447. Out of 14800 testing images, the algorithm was able to predict 10142 images correctly leading to an accuracy of 68.52702702702703 %.
The algorithm works well for 2000 iterations with a reasonalble computation time.

KNN :- 
With help of repeated list comprehensions and list.append, the algorithm was implemented. Due to the slow nature of this algorithm, I chose to consider at max 100 Testing examples. Also due to a high number of calculations Jupyter crashed in the middle of computation. Hence use of 100 Testing Examples is justified. An accuracy of 89% was obtained fot the first 100 testing examples.
Due to the slow nature of this algorithm, its use must be restricted to small testing and training datasets.

Neural Network :- 
With the help of backpropagation, the algorithm was implemented. It involves 1 input layer, 1 hidden layer and 1 output layer. Initially, the accuracy of the algorithm was observed to be 0 % and was predicting the same output within a row. But with the help of Xaverian Initialization, the accuracy improved to 5.236486486486487 % and 5.405405405405405 when weights are initialized randomly and as ones respectively.
The accuracy indicates the presence of a bug in implementation of Backpropagation.

K-Means Clustering :- 
The implementation of the algorithm is incomplete.
