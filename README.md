# SVM

Implemented linear support vector machines to classify mnist_data.mat, spam_data.mat, and cifar10_data.mat (NOTE: mnist_data.mat and cifar10_data.mat were too large to add to repository). I started by partitioning the raw data into training and visualization data, then using classification accuracy to measure error rate for the training and validation sets after training the linear SVM. Lastly, I trained the model with different hyperparameters using k-fold cross validation to determine the best regularization parameter C in the soft-margin SVM algorithm.

Execute cells for Questions 1-5 to obtain the results I used for my kaggle predictions. 

For my kaggle submissions, my MNIST prediction is listed under the username 'hw' and my SPAM and CIFAR predictions are listed under the username 'mmchicken':

https://www.kaggle.com/c/spring20-cs189-hw1-spam/leaderboard

https://www.kaggle.com/c/spring20-cs189-hw1-cifar10/leaderboard

https://www.kaggle.com/c/spring20-cs189-hw1-mnist/leaderboard
