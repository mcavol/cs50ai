For 1 pooling adn 1 convolutional layers result is: 
333/333 - 1s - 4ms/step - accuracy: 0.0550 - loss: 3.4944

For 2 pooling adn 2 convolutional layers result is: 
333/333 - 2s - 5ms/step - accuracy: 0.9589 - loss: 0.1551

So for 2 layers result is significantly better

For using 64 filters instead of 32 for convolution result is:
333/333 - 2s - 7ms/step - accuracy: 0.9509 - loss: 0.1739
So, it's longer, but accuracy is the same.

For using 3x3 matrix for pooling instead of 2x2 result is:
333/333 - 1s - 4ms/step - accuracy: 0.6780 - loss: 1.0181
So it's faster, but lower accuracy.

For using 256 neurons instead of 128 in hidden layer result is:
333/333 - 2s - 5ms/step - accuracy: 0.9481 - loss: 0.2202
So it's almost the same as 128 neurons

For using 2 hidden layers with 128 neurons each result is:
333/333 - 2s - 5ms/step - accuracy: 0.7734 - loss: 0.6852
So it's even worse then for 1 layer

For using 2 hidden layers with 64 neurons each result is:
333/333 - 2s - 5ms/step - accuracy: 0.0545 - loss: 3.5079
So it's much worse