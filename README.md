## Random-Digit-Predictor



### Modules:

##### Module 1: Interface

Web application was created with the use of Streamlit technology. Streamlit is a very recent technology and is perfect match for ML model visualization. The interface contains a button, which generates random predictions. It also contains a sidebar which will store the input image thus helping in verifying how accurate the model was to the given input image. interface also visualizes all the nodes from all the layers in Black and White color (Black being close to zero and White being close to One).  
 
##### Module 2: Prediciton
 
 In this project a simple Neural Network with two hidden layers and one output layer is implemented. Also, visualized the values of all the nodes of these layers. Random module from numpy is used to obtain random image from the mnist dataset. The image is then passed through neural network, and then atlast predicting the value for the given image/digit. This project involves simple server creation in Flask, to serve the neural network model for inference. Keras functional API's were used to obtain the values of nodes of the hidden layers along with output layer. 
 
 ##### Some sample images of the applications :
 1. Input Layers
 <img src="images/input_layers.jpg" height="250" alt="my image">
 
 2. SideBar for input image
 <img src="images/side_bar.jpg" height="250" alt="my image">

3. Output Layer
<img src="images/output_layer.jpg" height="250" alt="my image">
