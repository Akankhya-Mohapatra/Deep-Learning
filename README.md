In this course, Professor Jian Tang, MILA had assigned the task to carry out the following:
•	Implement a convolutional neural network for image classification on CIFAR-10 dataset
•	Implement a recurrent neural network with/o LSTM for sentiment analysis using SST dataset


In this assignment, I have worked on Tensor operations - squeezing/Unsqueezing, concatenation/stacking, expansion/reduction. Using Convolutional Neural network on CIFAR-10 dataset with 'Adam' optimizer, I obtained a test accuracy of 0.5231 and conclude basis the structure constructed that increasing the no of layers will extract more features from images until the model starts to overfit. Optimum variation in hyperparameters plays a key role in achieving the same.

For sentiment Analysis, I used RNN to classify sentences into positive, negative and neutral sentiments for each sentence. For this purpose we use SST dataset. We need an embedding layer to transform words into word embeddings, a RNN layer to transform word embeddings into sentence encodings, an activation function, and a linear layer as well as a softmax function for sentence classification. I obtain the accurate measure of hyperparameters and implement forward function and finally compared the different optimizers used during tuning. I conclude here that till the point where validaiton loss and training loss keeps decreasing, we may increase epochs. Once loss starts to increase, it is an indication for overfitting and we should not further test for increased epochs. 

A good model should be able to generalize well and therefore, to achieve a good model, I begin with default values before increasing/decreasing to understand a pattern and then determine the best model of all.
