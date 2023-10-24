## Hand written digit recognition using Neural Network 

This repository contains Python code for a simple neural network digit classifier implemented from scratch using Numpy. The neural network is trained on the MNIST dataset, a large database of handwritten digits. The model uses a shallow neural network architecture with one hidden layer and ReLU activation functions.

### Prerequisites
- Python 3.x
- Numpy
- Pandas
- Matplotlib

### Neural Network Architecture

The neural network consists of the following layers:
- Input layer: 784 neurons (corresponding to 28x28 image pixels)
- Hidden layer: 10 neurons with ReLU activation
- Output layer: 10 neurons with softmax activation (for digit classification)

### Workflow

1. **Data Loading:**
   - The MNIST dataset is loaded from the `train.csv` file using Pandas.

2. **Data Preprocessing:**
   - The data is shuffled and split into development and training sets.
   - Input features are normalized to values between 0 and 1.

3. **Neural Network Training:**
   - The neural network parameters are initialized.
   - Forward propagation and backward propagation are implemented.
   - Gradient descent is used to optimize the weights and biases.

4. **Prediction:**
   - Trained model is used to make predictions on both training and development sets.
   - Predictions are compared with actual labels to calculate accuracy.

5. **Visualization:**
   - Sample predictions from the training set are displayed with corresponding labels.

### Results

The accuracy of the model is evaluated on the development set. You can modify hyperparameters such as learning rate and number of iterations to observe how the accuracy changes.

Feel free to explore and modify the code for your own learning and experimentation!
