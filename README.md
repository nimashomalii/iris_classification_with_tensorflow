# iris_classification_with_tensorflow
The Iris dataset is one of the most well-known datasets in the field of machine learning and statistics. It consists of 150 samples from three different species of Iris flowers: Iris setosa, Iris versicolor, and Iris virginica. The dataset is designed for classification tasks, where the goal is to predict the species of the Iris flower based on four input features. These features include the sepal length, sepal width, petal length, and petal width, all measured in centimeters. The dataset is often used to test and benchmark machine learning algorithms for classification tasks, as it is simple, well-structured, and easy to understand. The primary task is to classify the flowers into one of the three species based on these features.
We built a model where the input consists of four features, and the output is the predicted category of the flower. In this model, a 4-layer neural network is used. The first three layers each contain 20 neurons with the ReLU activation function, and the final layer has three neurons with the softmax activation function. After training the model for 17 epochs, its accuracy reached 97%. The following images show the accuracy and loss function plots with respect to epochs.
![image](https://github.com/user-attachments/assets/df7f6cc0-7007-4f41-b822-c62d886023da)
