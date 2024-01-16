# Introduction 
This Kaggle project utilized Keras to build a Convolutional Neural Network to identify whether an image is a cat or a dog. The CNN is built with Keras pre-trained model Xception, scoring around 90% of accuracy on validation data. 

# Data Set
###### The data source can be found here: [https://www.kaggle.com/c/dogs-vs-cats-redux-kernels-edition/data]. 
1. Utilize Kaggle API to import data
2. For model training, sub-sampled 80% of training data to lower the RAM consumption; hence there would be 10,000 for each category
3. Declare the input image dimension as 128x128, with 3 channels

# Performance Summary
Trained with 30 epochs, the model scores around 90% accuracy in training and validation data set.

<img width="580" alt="截圖 2024-01-16 下午12 04 06" src="https://github.com/YenChenHsu/kaggle-cat-dog-classification/assets/57134574/9fa7ba96-909c-4d7c-9271-9a8e73d02f8b">
