# Logisitic Regression in the form of a Neural Network

The point of this model is to write a network from scratch (no Keras, Tensorflow, etc.) to classify images of cats and dogs.

This personal project was inspired by Andrew Ng's [Deep Learning course](https://www.coursera.org/specializations/deep-learning) on Coursera.

I wanted to implement Logistic Regression in the form of neural network (with one layer and one unit) and then build up to a shallow network and then a full network, leveraging deep learning libraries later on to improve performance. They say you have to write a neural network from scratch to fully understand how a neural network works. I have never done the nitty gritty implementation myself. Therefore, I've implemented the critical functions which include propagating through the network, calculating the loss, optimization, prediction, etc. 

I used a [dataset](https://www.kaggle.com/c/dogs-vs-cats-redux-kernels-edition/data) from an old Kaggle competition where teams were supposed to develop a model to predict cat or dog. 

### Data:
* The original dataset consisted of 25000 images. To simplify things and run on a local Jupyter notebook, I cut it down to 2000 training images and 1000 test images. The comments should explain this process clearly. 
* The images were fairly high resolution, but all different. In order to create uniformity, they were reformatted to each be 128x128px. 
