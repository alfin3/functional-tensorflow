# functional-tf-nn

The commonly used libraries for implementing, training, and evaluating learning algorithms often improve usability at the expense of composability and research flexibility. However, a trade-off is not required to achieve a higher relational abstraction level.

The provided segmentation of neural network model construction with closure, implemented within the constraints of a commonly used library (TensorFlow), improves usability and composability while providing the flexibility for modifications such as experimenting with dropout and pruning schemes and accessing gradients.

# functional-tf-nn/feedforward
Build a fully connected feedforward neural network from a topology list:

1) build layer functions
2) compose layer functions into a model function
3) evaluate the model function

# functional-tf-nn/lstm
Build a multilayer LSTM from a topology list: 

1) build a cell function for each layer
2) build layer functions from cell functions
3) compose layer functions into a model function 
4) evaluate the model function


