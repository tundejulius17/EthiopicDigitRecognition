# EthiopicDigitRecognition
.

Character recognition is one of the first fields where machine learning was used. Among the first extensive experiments was the MNIST dataset, handwritten digits 0...9 collected from US postal envelopes. Since this classic benchmark collection, a number of MNIST-like datasets have been collected; for example the Fashion MNIST dataset consisting of pictures of 10 different clothing classes.

Recently, the list of MNIST's was extended by Afro-MNIST, a synthetic MNIST-style dataset for four orthographies used in Afro-Asiatic and Niger-Congo languages. This competition hosts a modified version of the Ge`ez (Ethiopic) dataset published in the paper [1].

The competition is part of Tampere University (TAU) course DATA.ML.200 Pattern Recognition and Machine Learning in the Fall semester 2020. The competition was hosted on Kaggle.

[1] Daniel J Wu, Andrew C Yang, Vinay U Prabhu, "Afro-MNIST: Synthetic generation of MNIST-style datasets for low-resource languages," in ICLR 2020 Practical Machine Learning for Developing Countries workshop.
# Overview 
A convolutional neural network model to classify Ethiopic digits in an MNIST-like competition. 
# Dataset
The dataset contains 60000 bitmaps of size 28x28. The dataset was further divided into training and validation datasets with 45000 and 15000 images respectively. The test dataset contains 10000 bitmaps.
# Libraries
Keras, TensorFlow
# Metrics
The model achieved 99.76 % on Kaggle leader board.
