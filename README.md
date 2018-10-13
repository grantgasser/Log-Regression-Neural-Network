# Logisitic Regression in the form of a Neural Network

TODO: 
* Implement optimization and train function
* Predict on test data
* Clean up comments and write full description

This personal project was inspired by Andrew Ng's [Deep Learning course](https://www.coursera.org/specializations/deep-learning) on Coursera.

I wanted to implement Logistic Regression in the form of neural network and then build up to a shallow network and then a full network, leveraging deep learning libraries to improve performance. They say you have to write a neural network from scratch to really appreciate the complexities and the beauty of the model. Though I've used Keras and Tensorflow before, I had never done this until now. Therefore, I've implemented the critical functions myself which include propagating through the network, calculating the loss, gradients, etc. 

I used a [dataset](https://www.kaggle.com/c/dogs-vs-cats-redux-kernels-edition/data) from an old Kaggle competition where teams were supposed to develop a model to predict cat or dog. 

### Notes:
* The original dataset consisted of 25000 training images and 12500 test images. To simplify things and run on a local Jupyter notebook, I cut it down to 2000 and 1000 respectively. This made the code a bit sloppy, but the comments should explain it clearly. 
