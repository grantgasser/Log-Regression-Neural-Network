# Logisitic Regression in the form of a Neural Network

TODO: 
* Implement optimization and train function
* Predict on test data
* Clean up comments and write full description

This personal project was inspired by Andrew Ng's [Deep Learning course](https://www.coursera.org/specializations/deep-learning) on Coursera.

I wanted to implement Logistic Regression in the form of neural network (with one layer and one unit) and then build up to a shallow network and then a full network, leveraging deep learning libraries to improve performance. They say you have to write a neural network from scratch to fully understand how a neural network works. Though I've used Keras and Tensorflow before, I had never done the nitty gritty implementation myself. Therefore, I've implemented the critical functions which include propagating through the network, calculating the loss, gradients, etc. 

I used a [dataset](https://www.kaggle.com/c/dogs-vs-cats-redux-kernels-edition/data) from an old Kaggle competition where teams were supposed to develop a model to predict cat or dog. 

### Data:
* The original dataset consisted of 25000 training images and 12500 test images. To simplify things and run on a local Jupyter notebook, I cut it down to 2000 (1000 cats, 1000 dogs) and 1000 (500 cats, 500 dogs) respectively. This made the code a bit sloppy, but the comments should explain it clearly. 
* The images were fairly high resolution, but all different. In order to create uniformity, they were reformatted to each be 128x128px. 
