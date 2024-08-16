# Neural_Network_0-1_OCR
>In this workshop, conducted under IEEE at SIES Graduate School of Technology, we developed an Optical Character Recognition (OCR) system to classify handwritten digits (0-9) using the MNIST dataset. The project involved creating a fully connected neural network from scratch to handle digit classification tasks emphasizing on learning core principles of machine learning, including network architecture, activation functions, and optimization techniques.

## Key Concepts:
### Computed a single neuron using the formula:
$$ \text{neuron output} = \mathbf{input} \cdot \mathbf{weight} + bias $$
#
### Computed a multiple neuron also known as a layer of neurons using the formula:
$$ \text{output} = \sum_{i=0}^{n} (\text{input}_i \cdot \text{weight}_i) + \text{biases} $$
#
### Activation Function: Applied ReLU:
$$ \text{ReLU}(x) = \max(0, x) $$
#
### SoftMax Activation: 
$$ \text{Softmax}(z_i) = \frac{e^{z_i}}{\sum_{j} e^{z_j}} $$
#
### Loss Function: Used Cross-Entropy Loss:
$$ \text{Loss} = -\sum_{i} y_i \log(p_i) $$
#
### Adam Optimization: Updated weights using Gradient Descent:
$$\theta_t = \theta_{t-1} - \frac{\alpha \cdot \hat{v}_t}{\sqrt{\hat{m}_t} + \epsilon}$$

## Credits
A special thank you to **Aditya Dikonda** for leading and guiding the workshop. His expertise and support were invaluable throughout the training process which provided valuable insights and guidance throughout the session.

For more information or inquiries, you can reach out to him on:
+ GitHub - [Aditya Dikonda](https://github.com/Adityadikonda10)
+ LinkedIn - [Aditya Dikonda](https://www.linkedin.com/in/aditya-dikonda-144141286)
