# Exercise MNIST classification with MLP
In these few rows of code is shown how to make a classification of the MNIST dataset using a Multilayer Perceptron.

This is a naive example, in fact here we don't control every single layer of the NN (for example we can use only 1 kind of application functions), if we want to be more flexible it's better to use different libraries like Keras or Pytorch instead of Sklearn.

To speed the code is better to use a PCA before the training, in this way the training and convergence will be easier and faster.

If you have some questions, suggestions or you notice mistakes I will be happy to talk with you.

I've studied the fundamentals from the course of Machine Learning in Python developed by Profession.AI, if you want to know more about these topics I'm happy to recommend you this course :)
## Dataset
If you want to run the code on your device make sure that you've downloaded (and put on the same folder of your code) the 4 files of MNIST dataset, you can find them clicking [here](http://yann.lecun.com/exdb/mnist/)
## What is MNIST?
The MNIST (Modified National Institute of Standards and Technology database) is a database containing 70000 handwritten images in white and black.

In the images are drawn numbers between 0 and 9, so the program will try to understand what number is represented in a given image 
