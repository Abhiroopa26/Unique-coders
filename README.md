# Naive Bayes Classifier for Tennis Data

## Overview
This Python script implements a Naive Bayes classifier to predict whether to play tennis based on weather conditions. It reads a dataset from a CSV file containing metadata and training data, splits it into training and test sets, and then classifies the test set instances.

## Prerequisites
- Python 3.x
- NumPy library
- CSV module

## Files
- **tennis2.csv**: CSV file containing metadata and training data for the Naive Bayes classifier.
- **naive_bayes_tennis.py**: Python script implementing the Naive Bayes classifier.

## Usage
1. Ensure you have Python 3.x installed on your system.
2. Install NumPy library if not already installed:
3. Place the `tennis2.csv` file in the same directory as the Python script `naive_bayes_tennis.py`.
4. Run the script using the following command:

## Functionality
- **read_data(filename)**: Reads data from a CSV file.
- **splitDataset(dataset, splitRatio)**: Splits the dataset into training and test sets based on the specified ratio.
- **classify(data, test)**: Performs Naive Bayes classification on the test set.

## Example
```python
metadata, traindata = read_data("tennis2.csv")
splitRatio = 0.6
trainingset, testset = splitDataset(traindata, splitRatio)
training = np.array(trainingset)
testing = np.array(testset)
classify(training, testing)
