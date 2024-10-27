
Objective
------------------------------------------------------------
The goal is to build a multiclass classification model using Keras with TensorFlow backend to classify fashion items from the Fashion MNIST dataset using ANN.

Dataset Description
-------------------------------------------------------------
 The dataset contains 28x28 grayscale images of 10 different fashion categories.
Fashion MNIST consists of 70,000 images, where:
60,000 images are for training
10,000 images are for testing
Each image belongs to one of 10 classes:

-T-shirt/top

-Trouser

-Pullover

-Dress

-Coat

-Sandal

-Shirt

-Sneaker

-Bag

-Ankle boot

Steps to Run the Code
---------------------------------------------------------------
1-Download the Notebook

2-Open google colab

3-Create a New Notebook.

4-Install Required Packages.

pip install tensorflow keras matplotlib seaborn scikit-learn


5-Run the code by pressing (shift+enter)


Dependencies
--------------------------------------------------------------
-tensorflow: Used for building and training the neural network.

-keras: A high-level neural networks API, running on top of TensorFlow.

-matplotlib: For data visualization.

-seaborn: For enhanced data visualization, particularly the confusion matrix.

-scikit-learn: For model evaluation metrics.


Expected Results and Model Performance
---------------------------------------------------------------
After running the training process, you can expect the model to achieve a test accuracy of around 90% or higher depending on the hyperparameters and model architecture.

The following performance metrics will be printed:

-Classification Report: Includes precision, recall, and F1-score for each class.

-Confusion Matrix: Visual representation of the model's predictions compared to the actual classes.

-Training and Validation Accuracy and Loss: Plots showing how the model's accuracy and loss evolved during training.
