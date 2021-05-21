# Traffic-Sign-Classifier-usingCNN-Tensorflow-and-Open-Cv

Today’s more advanced technologies are furthering our goals and helping with automation in every field making the need for a human in those areas invalid, because a human is prone to making mistakes, but a machine in his/her place would certainly be more efficient, both in terms of speed and accuracy. Technologies such as Deep Learning and Machine Learning have evolved greatly in this time.

This technology helps to teach machines to learn on their own instead of having to program every single action and possibility. So, this project helps us to use techniques like this such as convolution neural networks, keras, Tensorflow, etc. and implement them so as to help the self-driving cars to be able to perceive traffic signs and react according to the input received.

In this project, we will build a deep neural network model that can classify traffic signals present in the image into different categories. With this model, we are able to understand and read traffic signals, which is very important to self-driving cars because it can otherwise lead to road accidents.

The main objective of this project is to develop a product which would help people learn about one of most underrated, yet very import part of our daily life, a traffic sign. This model has been made using deep learning libraries Tensorflow and its high level API, Keras. The objective of this model is to attain an accuracy so strong that an individual should be able to use our product without any hesitation.

In the past and recent times, there have been many road accidents where the main reason for these being inadequate knowledge of road and traffic signs. Even though speed is one of the key issue for the cause of such atrocities, in a survey, it was found out that the second most heard reason was an individual not knowing what a particular traffic sign meant.
Our team strongly believes that the product that we have developed would help individuals learn these signs intuitively, especially the adolescence of 21st century, who also stay and live around technology, which is growing faster than ever.

Our project focuses on detecting traffic signs, when provided an image to it through deep learning, image processing through OpenCV and a convenient UI is has been developed in Python GUI using Tkinter.

Initially after downloading the data set, the whole training of the model has been done in Anaconda. The images were initially divided into training and testing sets and were loading into the notebook using the OS module in python.
Then the required dependencies have been installed for training the network. Then the images for training have been loaded and are reshaped to have the same shape, to help the CNN model for training.

Then the outputs have been converted to categorical values. We have developed our own architecture for this project. Our architecture consisted of 2 sets of 2 convolution layers followed a max pooling layer and a dropout ratio has also been provided.

A validation split was also mentioned at the starting of training of the model, which helped us understand how our model was working after every epoch. After the whole model was trained, we also performed a test using the test set, and our trained model achieved an accuracy of 96%, which is considered very strong, taking the accuracy into account.
Then we have saved our model as h5 file in order to use it in our GUI. We have developed a python GUI using Tkinter, where a user can upload an image of a traffic sign and we predict that sign and display it back to the user.



