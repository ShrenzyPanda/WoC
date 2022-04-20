# WoC
Linear Regression :- 
With the help of gradient descent, the algorithm was implemented. The mean squared error on the training data (cost function) was found to be 1907.0986734578898 and on testing data, the mean squared error was found to be 2790.8495110921144.
Initially, I normalized the output values for the training and testing data, which resulted in the involvement of data leakage. Thus, normalization or standardization of only the input data must be done.

Polynomial Regression :- 
With the help of gradient descent, the algorithm was implemented. The dataset was checked till a polynomial of degree 3. The mean squared error obtained on training sets (cost function) were 62.340740826528695 and 71.69530953845312 for degree 3 and degree 2 repectively. The MSE obtained on testing data were 301675.1939167583 and 301882.2807949841 for degree 3 and degree 2 respectively.
The insanely high values of MSE on testing data indicate overfitting of training data in the model. Hence, regularization might be able to overcome this shortcoming.
Low cost can never assure that our model will perform well on our testing data. The reason being over-fitting of the hypothesis on our training data and our testing data not being similar to our training data. Initially I was using mean normalization but after replacing it with standardization, the cost for degree 3 and degree 2 polynomials were 36.85437846888681 and 65.4327304780402. The MSE obtained on testing data were 60.77484745657237 and 48.604307588836214 for degree 3 and degree 2 polynomials respectively.

Logistic Regression :- 
With the help of gradient descent and one vs all classifier, the algorithm was implemented. The cost function i.e. Binary Cross Entropy was found to be equal to 2.0561311357222447. Out of 14800 testing images, the algorithm was able to predict 10142 images correctly leading to an accuracy of 68.52702702702703 %.
The algorithm works well for 2000 iterations with a reasonable computation time.

KNN :- 
With help of repeated list comprehensions and list.append, the algorithm was implemented. Due to the slow nature of this algorithm, I chose to consider at max 100 Testing examples. Also due to a high number of calculations Jupyter crashed in the middle of computation. Hence use of 100 Testing Examples is justified. An accuracy of 89% was obtained for the first 100 testing examples.
Due to the slow nature of this algorithm, its use must be restricted to small testing and training datasets.

K-Means Clustering :- 
I faced difficulties in the understanding and implementation of this algorithm; therefore I wrote this algorithm for one iteration and then with the help of a function, I used it for all the iterations. After clustering, I evaluated the Dunn Index for the clusters and it was equal to 0.17288231039992585. Thus it is a poor algorithm for the given dataset as indicated by the Dunn Index.

Neural Network :- 
With the help of backpropagation, the algorithm was implemented. It involves 1 input layer, 1 hidden layer and 1 output layer, hence, it is a 2 Layer Neural Network. Initially, the accuracy of the algorithm was observed to be 0 % and was predicting the same output within a row. But with the help of Xavier Initialization, the accuracy improved to 5.236486486486487 %. After rechecking the backpropagation implementation, it was found that the derivative of the sigmoid function was not taken into account by me. Thus, due to the violation of the chain rule of derivatives, the implementation was faulty. After making the necessary changes, the accuracy boomed to 50.57432432432433 %. After tuning the hyperparameters, an accuracy of 67.89864864864865 % was observed.  
Due to the error prone nature of the algorithm, caution must be taken while computing gradient and one must check that the chain rule of derivatives is followed. 

