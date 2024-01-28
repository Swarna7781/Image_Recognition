The CIFAR-10 dataset (Canadian Institute for Advanced Research, 10 classes) is a subset of the Tiny Images dataset and consists of 60000 32x32 color images. The images are labelled with one of 10 mutually exclusive classes: airplane, automobile (but not truck or pickup truck), bird, cat, deer, dog, frog, horse, ship, and truck (but not pickup truck). There are 6000 images per class with 5000 training and 1000 testing images per class.

Since this particular dataset is contained in keras so i have directly loaded it in my jupyter environment. The objective of this model is, among the 10 classes of images whenever the model is given a random image it predicts the class name of that image. For example, i have given an image of a ship so output will be "The prediction is : ship".

Following are the things that i have used in this code:
> OpenCV ( To take any image as an input)
> Tensorflow, keras ( since we are building a deep learning model, these will add layers to get our data filtered. Here we are using, CNN (Convolution Neural Network)
  to filter our images data which includes Conv2D, MaxPooling)
> L1 Regularizer and Dropout ( L1 is also called lasso regularizer and Dropout to handle the issues of overfitting)
> matplotlib ( To visualize the images)
> Numpy
> Finally, a classification report about my model performance from scikit-learn.

