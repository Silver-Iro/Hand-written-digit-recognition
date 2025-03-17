## Hand writing recognition neural network.

**Summary**
A sequential neural network to recognize hand written digits from MNIST dataset.
Trained on over 60,000 greyscale samples.

**Tools and Libraries**

 - Wsl
 - python 3
 - [Jupyter notebook](https://jupyter.org)
 - [TensorFlow](https://www.tensorflow.org)
 - [numpy](numpy.org)
 - keras
 - MINST data set
 - matplotlib

**Usage**
 1. To use this model, clone the repository and run the training   
    notebook.
 2. Format the image/s for prediction as 28x28 images reshaped in a
   single array (ndim=1 per image), each digit must be put in a separate
   image for better results.
 3. run the model and print/plot the prediction output (y) for final
   results.


**Methodology** 
importing and processing of MNIST hand written digits dataset, building and training a sequential network with 10 outputs running sigmoid activation function, and finally testing the model in 10,000 samples to measure the accuracy.
adding one more hidden layer to the model was able to achieve higher accuracy.

**Further testing**
a small set of external digits was hand written and added to [Test_images/](Test_images/) folder, the models was able to successfully identify that set as well.

**Results**

model 1 (10 -> 10 neurons)
accuracy: 0.917
![Model 1 heatmap](results/Model1.png?raw=true)
_______

model 1 (10 -> 10 neurons)
accuracy: 0.973
![Model 2 heatmap](results/Model2.png?raw=true)
