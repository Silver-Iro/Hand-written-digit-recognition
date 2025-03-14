## Hand writing recognition neural network.

**Summary**
A sequential neural network to recognize hand written digits from MNIST dataset.
Trained on over 60,000 greyscale samples.

**Tools and libraries**

 - Wsl
 - python 3
 - [Jupyter notebook](https://jupyter.org)
 - [TensorFlow](https://www.tensorflow.org)
 - [numpy](numpy.org)
 - keras
 - MINST data set
 - matplotlib

**methodology** 
importing and processing of MNIST hand written digits dataset, building and training a sequential network with 10 outputs running sigmoid activation function, and finally testing the model in 10,000 samples to measure the accuracy.

**usage**
 1. To use this model, clone the repository and run the training   
    notebook.
 2. Format the image/s for prediction as 28x28 images reshaped in a
   single array (ndim=1 per image), each digit must be put in a separate
   image for better results.
 3. run the model and print/plot the prediction output (y) for final
   results.
