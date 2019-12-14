# TensorFlow-Object-Detection-Candlestick-chart-doji-pattern
Using tensorflow API creating doji candlestick recognizer

Doji pattern detection can be done via manual coding on stock data in csv file using pandas library.
But I wanted to try my first step into Computer Vision world using Tensorflow.

# Output files

![Object detector 1](https://user-images.githubusercontent.com/50289281/64172492-bb91d100-ce72-11e9-8d85-68a07196466b.png)
![Object detector 2](https://user-images.githubusercontent.com/50289281/64172493-bc2a6780-ce72-11e9-83b1-3fb90f0e230c.png)
![Object detector 4](https://user-images.githubusercontent.com/50289281/64172494-bc2a6780-ce72-11e9-967d-7742275eb8f7.png)
![Object detector 3](https://user-images.githubusercontent.com/50289281/64172491-bb91d100-ce72-11e9-8e86-06b7637ec97e.png)

# What is Doji candlestick?

In stock market technical analysis terminology a Doji candlestick is when prices finish very closer to each other.
You can see the example in below image:

![doji 001](https://user-images.githubusercontent.com/50289281/64168420-1cb4a700-ce69-11e9-821d-be0138873627.png)

# About Model
Here I have created a doji candlestick detector by using tensorflow API

Model used : faster_rcnn_inception_v2_coco_2018_01_28

No. of train images used : 40

Labellmg is used for labeling training images.

batch size : 1

# Future scope

Make profitable pattern recognition using Elliot wave theory

# Credits:

Stack Overflow
