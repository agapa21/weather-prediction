In our project we used neural networks feedforward. Information flows only in one direction - from input to output. We used the TensorFlow framework to create neural networks. We created Sequential model, in which we defined the layers of the network:
* input layer, accepting input data,
* hidden layers, relu activation function,
* output layer, number of neurons 27 (equal to the number of classes, i.e. different values in output column), softmax activation function,
Then, using the model.compile function, we assumed the parameters of the network:
* loss sparse_categorical_crossentrop function
* adam optimizer
* accuracy and sparse_categorical_crossentropy metrics
