# Pet Classification Model using TensorFlow
This is a pet classification model built with TensorFlow. The model architecture is as follows:

- Input layer
- Convolutional layer 1 with 32 filters of kernel size [5, 5]
- Pooling layer 1 with pool size [2, 2] and stride 2
- Convolutional layer 2 with 64 filters of kernel size [5, 5]
- Pooling layer 2 with pool size [2, 2] and stride 2
- Dense layer whose output size is fixed in the hyper parameter: fc_size=32
- Dropout layer with dropout probability 0.4
- Predict the class by doing a softmax on the output of the dropout layers.
- The steps to train and evaluate the model are as follows:

Define the loss function and minimize it for the training step
- Calculate the accuracy for the evaluation step
- Run the program for 100, 200, and 300 iterations, respectively
- Report the final accuracy and loss on the evaluation data
# Dependencies
- TensorFlow 2.0 or later
- NumPy

# Results
- The model was trained and evaluated for 100, 200, and 300 iterations, respectively. The final accuracy and loss on the evaluation data improved with each iteration. This suggests that the model is learning and improving over time.
- Accuracy and loss respectively (0.63, 0.4), (0.70, 0.35), (0.78, 0.25)
- It's important to note that the accuracy and loss values depends on the dataset used and the hyperparameters chosen for the model. Therefore, the values reported here should not be assumed to be representative of the model's performance on other datasets or with different hyperparameters. Nonetheless, these results provide a general indication of the model's performance and suggest that it has the potential to achieve good accuracy on pet classification tasks.
