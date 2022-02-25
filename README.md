# hand_writting_recognition_project.

Deep Neural Network with Keras for MNIST handwritten classification and recognition

## Section D : Load the data in

Let's load in the dataset using Keras
from keras.datasets import mnist 


(trainsetX, trainsety),(testsetX,testsety) = mnist.load_data()

print('Train: X = {}, y = {}'.format(trainsetX.shape, trainsety.shape)) 

print('Test: X = {}, y = {}'.format(testsetX.shape, testsety.shape))

##Section I.I : Initial Data Indagation

Start off by understanding what MNIST Data is in more detail

Note down the dimensions and other practical information about the MNIST dataset

Load in the dataset into your Colab Environment [Using Keras Datasets]

## Section I.II : Initial EDA

Explore the datasets descriptive statistics if needed

Create graphs of the counts of each class

Make deductions upon the class distribution

##Section II : Data Preparation

Normalize the pixel value of the all images

Why is scaling of the pixel value required ? Make a note

Explain the difference between pre-processed images and the normalized images

## Section III : Model Construction

What sort of Neural Network would you employ for this problem statement ?

Write down the skeleton flow of the model

Create a baseline model

Train the model

##Section IV : Model Evaluation

It is recommeded to to use Kfolds to evaluate your model, what other validation process could you employ ?

What would be the best value for K and why for this baseline model

Evaluate the model accordingly and make a note of it's performance with respect to it's accuracy

## Section V : Model Evaluation Metrics

Create Graphical plots of the model performance on the train and test set during individual folds

Is your model overfitting , underfitting or has the optimum fit ? Provide reasoning

Get the loss and validation loss of the model and also the accuracy and the validation accuracy

What are your inferences about the model performance ? Can you summarize your observations ?
