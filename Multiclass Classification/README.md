## Learnings

* For n classes, end with a dense output layer with n neurons.
* Multiclass classification should end with softmax for the output layer.
* Categorical crossentropy is used as a loss function for multiclass classification.
* One-hot encoding to vectorize the computation.
* Avoid intermediate hidden layers that are smaller than the output layer.
