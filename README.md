# SimpleObjectRecognition
#### Group name:A+++++               Section: 2

### Brief introduction to what we have done
Here we use the Convolutional Neural Network (CNN) and Keras to build a model to classify images. After finishing the model training and testing, a graphical user interface(GUI) is built to facilitate the application of this code trunk.

### What is CNN?
A CNN is a supervised learning technique which needs both input data and target output data to be supplied. These are classified by using their labels in order to provide a learned model for future data analysis.

Typically a CNN has **three main constituents** - a **Convolutional Layer**, a **Pooling Layer** and a **Fully connected Dense Network**. The Convolutional layer takes the input image and applies m number of nxn filters to receive a feature map. The feature map is next fed into the max pool layer which is essentially used for dimensionality reduction, it picks only the best features from the feature map. Finally, all the features are flattened and sent as input to the fully connected dense neural network which learns the weights using backpropagation and provides the classification output.

CNNs use **relatively little pre-processing** compared to other image classification algorithms. This means that the network learns the filters that in traditional algorithms were hand-engineered. This independence from prior knowledge and human effort in feature design is a major advantage.

[readmore](https://en.wikipedia.org/wiki/Convolutional_neural_network)  

### Data

Data in this project is devided into **three sections**. 
* **Testing data**: the data we use to build the models
* **Traning data**: untouched data to verify the effectiveness of the built model
* **Online data**: evaluate the CNN model from random images searched online and do some interesting application

### Installation instructions

In order to run the code above, you need to install some essential liabraries:
```pip install TensorFlow  ```


### Run instructions