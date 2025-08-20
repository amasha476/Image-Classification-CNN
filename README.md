## About the Project
This project focuses on a multi-class image classification problem implemented using Python.

### Tools used:
Python - CNN / Sequential models

### Dataset
https://www.kaggle.com/datasets/vencerlanz09/agricultural-pests-image-dataset

The dataset consists of images of 5 classes. ('grasshopper' , 'bees', 'moth' , 'wasp' , 'ants')

### Model Architecture
The model architecture is designed for image data and includes several convolutional and dense layers.

The model comprises the following layers:

**Convolutional Layer (Conv2D):**
* Applies 32 filters of size (3, 3) to the input image.

    **Activation function:** 
    * Rectified Linear Unit (ReLU).

**MaxPooling Layer (MaxPooling2D):**
* Performs max pooling with a pool size of (2, 2), reducing spatial dimensions.

**Dropout Layer:**
* Regularization technique that randomly deactivates 25% of neurons during training.

**Flatten Layer:**
* Converts the 2D output from the previous layers into a 1D array.

**Dense Layer (with ReLU activation):**
* Fully connected layer with 128 neurons.

    **Activation function:**
     * Rectified Linear Unit (ReLU).

**Dropout Layer:**
* Regularization technique that randomly deactivates 50% of neurons during training.


**Dense Layer (with Softmax activation):**
* Final layer with 5 neurons, representing classes in a multi-class classification task.
* Activation function: Softmax, producing a probability distribution over the classes.


### Model Performance

* Train loss: 0.2246
* Train accuracy: 0.9763 

* Test loss: 1.0484
* Test accuracy: 0.6057

<img width="566" height="306" alt="image" src="https://github.com/user-attachments/assets/5995b2e3-747c-4a49-a7cf-3de2df81e3b2" />





