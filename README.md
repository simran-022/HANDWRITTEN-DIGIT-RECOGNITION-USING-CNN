Introduction:

Everyday, developers are working hard on machines to make them more smart and intelligent by using machine learning and deep learning techniques so that they can perform tasks similar to humans. With the help of these techniques human effort can be reduced in recognizing, learning, predictions and many other areas.

The ability of computers to recognize human handwritten digits is known as handwritten digit recognition from sources such as paper documents, images, touch-screens etc.
In this projectp a deep learning model is used to achieve high performance on the handwritten digit recognition task using the MNIST dataset and build a GUI App based on Tkinter where, one can draw the digits (single as well as multiple) and recognize it straight away by drawing a bounding box surrounding each digit.

Problem Statement:

It is easy for the human to perform a task accurately by practicing it repeatedly and memorizing it for the next time. Human brain can process and analyse images easily. Also, recognize the different elements present in the images.
The challenge in handwritten digit recognition is mainly caused by the writing style variations of every single individual. So, it is not easy for the machine to recognize the handwritten digits accurately like the humans do. Hence, robust feature extraction is very important to improve the performance of machines


MNIST Dataset:

The MNIST dataset (Modified National Institute of Standards and Technology) is a large dataset of handwritten digits that is widely used for training and testing in the field of machine learning and deep learning.
The MNIST dataset contains 60,000 training images and 10,000 testing images of handwritten digits from zero to nine(0 to 9). So, the MNIST dataset has 10 different classes. Each image is represented as a 28×28 matrix where each cell contains grayscale pixel value.

Steps to implement the CNN handwritten digit recognition GUI App:

1.	Import the libraries and load the MNIST dataset
2.	Data Preprocess and Normalize
3.	Create the model
4.	Train the model
5.	Evaluate the model
6.	Create GUI to predict digits

