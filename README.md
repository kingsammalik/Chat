# Chat

This is a AI model built to classify images between a chat screen shot and a general pic in the gallery. 

In the model I have used two Convolutional2D layers with 3x3 filter size, and then max pooling layer. The output is then flattened out and then fed into a dense network layer with 128 neurons and finally into the output network layer with just one neuron to classify the image and ofcourse with sigmoid activation function.

I have also converted this model into tensorflow lite model to use it in the mobile application. 

![alt text](https://github.com/kingsammalik/Chat/blob/master/Screenshot%202020-04-25%20at%2011.20.07%20PM.png)
