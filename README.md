# Fashion-MNIST-Classification-using-Convolutional-Neural-Network-With-Keras

In this excercise/mini project I am trying to classify the Fashion MNIST dataset as I get myself acquainted with Convoltuional Layers in Keras.

Goal: Primary goal of this excercise is to equip myself with Keras set up with regards to a Covolutional Neural Network by implementing the LeNet-5 architecture. Secondary goal is to achieve atleast 90% success in predicting the right labels for the Fashion MNIST Images.

Dataset: Fashion-MNIST is a dataset of Zalando’s article images consisting of a training set of 60,000 examples and a test set of 10,000 examples. Each example is a 28×28 grayscale image, associated with a label from 10 classes and there're 6000 examples from each class. Fashion-MNIST is intended to serve as a direct drop-in replacement of the original MNIST dataset for benchmarking machine learning algorithms. You can read more about the dataset here (https://research.zalando.com/welcome/mission/research-projects/fashion-mnist/). The data is downloaded(called) from the Keras' dataset library.

Approach: First the dataset is loaded from the keras dataset package,the dataset is then reshaped and normalized. I then implement the pioneered LeNet-5 Architecture as the final Convolutional Neural Network model. Further we evaluate the model and do some analysis on the predictions made by the model.

Results: After training the Lenet-5 model for 40 epochs, the model attains an accuracy of 96.53% on the training set and an accuracy of 89.81% on test test and around 87% of images misclassified are similar in shapes suggesting that the model has not yet learned the nuances in shapes of different categories

Future Works: A deeper model would at best remove most of the misclassification problems and at worst have similar performance to that of LeNet-5. Further some regularization can also be added to lower the variance.

Dates: Feb 17th - 18th 2020
