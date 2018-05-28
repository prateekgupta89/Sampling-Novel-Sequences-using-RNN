# Sampling-Novel-Sequences-using-RNN
This is an example of an RNN model to sample novel dinosaur names.
We extarct dinosaur names from a txt file and use it to create a library. The model will have the following structure:
1) Initialize parameters
2) Run the optimization loop
   a) Forward propagation to compute the loss function
   b) Backward propagation to compute gradients with espect to the loss fucntion   c) Clip the graidents to avoid exploding gradients
   d) Using the graidents, update the paramaters with the gradient descent update rule.
3) After training the model, we use it to sample novel sequences.
