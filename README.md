# Neural Network Classifier for Tennis Data using Backpropagation

This Python script implements a neural network classifier using backpropagation to predict whether tennis matches will be played based on weather conditions.

## Files

- `neural_network_classifier.py`: Python script containing the implementation of the neural network classifier using backpropagation.
- `tennis2.csv`: Dataset containing training examples for the classifier.

## Usage

1. **Prerequisites**: Ensure you have Python installed on your system.
2. **Running the Script**:
    - Place the `neural_network_classifier.py` script and the `tennis2.csv` dataset in the same directory.
    - Open a terminal or command prompt.
    - Navigate to the directory containing the script and dataset.
    - Run the script using the command: `python neural_network_classifier.py`

## Implementation Details

- **Libraries Used**: The classifier is implemented using Python and may utilize libraries like numpy for numerical operations.
- **Algorithm**: Backpropagation is used to train a neural network classifier to predict whether tennis will be played based on weather conditions.
- **Neural Network Architecture**: The architecture of the neural network, including the number of layers, neurons per layer, activation functions, etc., can be customized within the script.

## Dataset

- **File**: `tennis2.csv`
- **Attributes**:
    1. Outlook: Weather outlook (Sunny, Overcast, Rainy)
    2. Temperature: Temperature (Hot, Mild, Cool)
    3. Humidity: Humidity level (High, Normal)
    4. Windy: Wind condition (True, False)
- **Target Variable**:
    - PlayTennis: Whether tennis was played (Yes, No)

## Results

- The script splits the dataset into training and testing sets using a specified ratio.
- It trains the neural network classifier using backpropagation on the training set.
- The trained classifier is then evaluated on the testing set to determine its accuracy.
- The script may also print additional performance metrics or visualization of the results, depending on the implementation.
