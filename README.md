Neural networks are the core of deep learning, a field that has practical applications in many different areas. Today neural networks are used for image classification, speech recognition, object detection, etc.
A single neuron transforms given input into some output.
I used the tanh activation function
The end goal is to find the optimal set of weights for this neuron that produces correct results. I did this by training the neuron with several different training examples.
At each step,I calculateD the error in the output of the neuron, and backpropagateD the gradients. The step of calculating the output of a neuron is called forward propagation while the calculation of gradients is called back propagation.
