Download Link :https://programming.engineering/product/theory-of-neural-networks/

# Theory-of-Neural-Networks
Theory of Neural Networks
1 Introduction

Artificial Neural networks (ANN) are inspired by the human brain structure. They are composed of several interconnected units, called neurons, capable of a single input-to-output trans-formation. There are usually several connections, and their properties are summarized in parameters called weights. In a Neural Network, neurons are organized in layers cascaded and connected to each other by patterns.

2 Theory of Neural Networks

A Neural Network is composed of a set of neurons. A neuron is a single unit that takes an input, makes a decision, and returns an output. It can receive inputs either from the outside world or from another neuron in the previous layer. Even the output of a neuron can be directed to the outside world or to a neuron in the following layer.

Each neuron is associated with a weight (w), that changes dur-ing the learning process accordingly to predefined rules, de-fined by the weight update procedure:

            wl+1 = wl + ∆wl
            	

            (1)

After defining the weight we can put into formulas the network (r) as:

            d
            	

            r = w · x = wixi
            	

            (2)

Where η is a (real positive) coefficient and tl is the target of xl. The perceptron rule guarantees convergence as stated by the following theorem:

If the training set is linearly separable, the perceptron learning procedure will find a separating hyperplane for it in a finite number of steps.

2.1 Adding layers to a Neural Network

If we add more layers to the network then we say that the ANN has multiple layers. The simplest multi-layer Neural Network is the one with one input layer, one inner layer (called hidden layer), and one output layer.

The input layer takes x and passes it to the hidden layer, then the hidden layer spreads its output to the output layer, which produces the output data.

As you can notice the hidden layer will be hidden from the outside of the neural network. The more hidden layers we have, the better the performances. However, if we add more hidden layers we will also require more computational power. Hence it is mandatory to find the correct balance between performances and number of layers.

2.2 Autoencoder

An autoencoder is a special type of multi-layer perceptron with two main characteristics:

        			

            					
            			
            			
            					
            					

Figure 1. Autoencoder (1 vs. 8).

Figure 2. Autoencoder (3 vs. 9). Figure 4. Autoencoder (2 vs. 5).

Figure 3. Autoencoder (1 vs. 7).
