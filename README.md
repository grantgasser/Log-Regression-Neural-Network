# Logisitic Regression in the form of a Neural Network

TODO: 
* Implement optimization and train function
* Predict on test data
* Clean up comments and write full description

This personal project was inspired by Andrew Ng's [Deep Learning course](https://www.coursera.org/specializations/deep-learning) on Coursera.

I wanted to implement Logistic Regression in the form of neural network and then build up to a shallow network and then a full network, levering deep learning libraries to do so. This first project is done "by hand," meaning I've implemented the functions to propagate through the network, calculate the loss, gradients, and so forth. 

I used a [dataset](https://www.kaggle.com/c/dogs-vs-cats-redux-kernels-edition/data) from an old Kaggle competition where teams were supposed to develop a model to predict cat or dog. 

### A few Notes:
* The original dataset consisted of 25000 training images and 12500 test images. To simplify things and run on a local Jupyter notebook, I cut it down to 2000 and 1000 respectively.
