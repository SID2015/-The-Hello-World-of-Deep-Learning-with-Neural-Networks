# -The-Hello-World-of-Deep-Learning-with-Neural-Networks
Creating a neural networks, where it learns the relationship between two numbers.

We have trained a deep neural network where it learns the relationship between two numbers

float train_function(float x){
    float y = (2 * x) - 1;
    return y;
}

# Step 1

Importing TensorFlow module and Keras libary.
We then import a library called numpy, which helps us to represent our data as lists easily and quickly

# Step 2

We will create the simplest possible neural network. It has 1 layer, and that layer has 1 neuron,
and the input shape to it is just 1 value.

The LOSS function measures the guessed answers against the known correct answers and measures 
how well or how badly it did.

It then uses the OPTIMIZER function to make another guess. Based on how the loss function went,
it will try to minimize the loss. At that point maybe it will come up with somehting like y=5x+5, which, while still pretty bad, is closer to the correct result (i.e. the loss is lower)


# Step 3

Compile the Neural Network
  
# Step 4
 
 Providing the Data
 
Next up we'll feed in some data. In this case we are taking 6 xs and 6ys. You can see that the relationship between these is that y=2x-1, so where x = -1, y=-3 et

# Step 5

Training the Neural Network.

The process of training the neural network, where it 'learns' the relationship between the Xs and Ys is in the model.fit call. This is where it will go through the loop we spoke about above, making a guess, measuring how good or bad it is (aka the loss), using the opimizer to make another guess etc


# Step 6

We can use the model.predict method to have it figure out the Y for a previously unknown X

Here, we need to know is that neural networks deal with probabilities, so given the data that we fed the NN with, it calculated that there is a very high probability that the relationship between X and Y is Y=2X-1, but with only 6 data points we can't know for sure. As a result, the result for 10 is very close to 19, but not necessarily 19.


![](/imgs/Training_NN.png)


![](/imgs/Output.png)

