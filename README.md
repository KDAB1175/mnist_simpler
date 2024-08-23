![Alt Text](https://cainvas-static.s3.amazonaws.com/media/user_data/cainvas-admin/mnist_keras.gif)

# mnist_simpler
Basic ML classifier on MNIST dataset. Built with Python and Pytorch

# Overview and specs
The default model runs for 20 epochs in training and has app. 95% accuracy after that time. It has two hidden layers. The input layer is 28x28 picture expressed in grey scale values from mnist_train.csv or mnist_test.csv. The hidden layers have 512 and 10 nodes respectively. The output layer has 10 nodes corresponding to 10 classification sections for number 0 through 9. The activation function between layers is always ReLU. Cross entropy loss function is at use here. The optimizer is SGD the whole thing, while learning rate is set as default to 0.1. All layers of this model are fully connected (aka. dense)

# Notes
The MNIST training csv file is not complete, for the complete file go to https://www.kaggle.com/datasets/oddrationale/mnist-in-csv
