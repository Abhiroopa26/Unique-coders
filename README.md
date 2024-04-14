# Backpropagation for Neural Network

This Python script implements a simple neural network using backpropagation to predict outputs based on input features.

## Usage

1. **Prerequisites**: Ensure you have Python installed on your system.

2. **Dataset**: Prepare your dataset in a suitable format. Ensure it is properly preprocessed and split into training and test sets.

3. **Running the Script**:
   
   - Adjust the filename in the code if your dataset has a different name.
   - Run the script using your preferred Python interpreter.

   ```bash
   python backpropagation_neural_network.py
   # Define your dataset and other parameters
input_size = 2
hidden_size = 3
output_size = 1
epochs = 1000
learning_rate = 0.01

# Create and train the neural network
model = BackpropagationNeuralNetwork(input_size, hidden_size, output_size)
model.train(training_data, training_labels, epochs, learning_rate)

# Evaluate the neural network on test set
accuracy = model.evaluate(test_data, test_labels)
print("Accuracy:", accuracy)
