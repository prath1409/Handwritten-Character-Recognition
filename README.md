# Handwritten-Character-Recognition

Here we will illustrate or demonstrate handwritten character recognition system using CNN model.

Abstract
An attempt is made to recognize handwritten characters for English alphabets using multilayer Feed Forward neural network. Kaggle dataset which consists of English alphabets and is in the form of .csv type are made use of to train the neural network. The feature extraction technique is obtained by normalizing the pixel values. Pixel values will range from 0 to 255 which represents the intensity of each pixel in the image and they are normalized to represent value between 0 and 1. Convolutional neural network is used as a classifier which trains the Kaggle dataset.

Block Diagram or system architecture.






![alt text](https://github.com/prath1409/Handwritten-Character-Recognition/blob/main/Images/block-diagram.PNG)

Prequistes:
1. Python(3.7.4 used)
2. IDE (Jupyter used)


Frameworks used:
1.Tensorflow(Keras uses TensorFlow in backend)
2.Keras
3.Numpy
4.cv2(openCV) (version 3.4.2)
5.Matplotlib
6.Pandas

Download Dataset:

The dataset for this project contains 372450 images of alphabets of 28×2, all present in the form of a CSV file:
https://www.kaggle.com/sachinpatel21/az-handwritten-alphabets-in-csv-format

Running the program
Go to the main file -> run main.py

python main.py

Result Screenshots

Alphabets

![alt text](https://github.com/prath1409/Handwritten-Character-Recognition/blob/main/Images/output-1.png)



![alt text](https://github.com/prath1409/Handwritten-Character-Recognition/blob/main/Images/output-2.png)
