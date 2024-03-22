# ML-assignment-2
This is a practice lab of neural network for handwritten digit recognition, neural network is one of the advanced learning algorithms and it originally comes from trying to mimic our human brain. Through neural network architecture, we can train an agent to recognize images, which is a remarkable example of the application of this algorithm.

To build the neural network architecture we use the Rectified Linear Unit (ReLU) function as activation. A multiclass neural network generates N outputs. One output is selected as the predicted answer. In the output layer, a vector 𝐳 is generated by a linear function which is fed into a softmax function. 

This is a multiclass classification task where one of n choices is selected. In this case, we use a neural network to recognize ten handwritten digits 0-9. Firstly we load the data set which contains 5000 training examples of handwritten digits. Secondly, we build tensorflow model layer by layer to train the neural network using ReLU function as activation and softmax regression as output function. Also, in exercise 2, we use Keras Sequential model and Dense Layer with a ReLU activation to construct the three layer network.

After examining the weights and defining the loss function, we use Keras to make a prediction. The results of the prediction are shown in the lab.
