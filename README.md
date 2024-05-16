## Bayesian Network for Heart Disease Prediction
## Overview:
This project involves using a Bayesian Network to predict the likelihood of heart disease based on various patient attributes. The Bayesian Network is constructed using the pgmpy library, which allows for the creation, training, and inference of probabilistic graphical models.

## Prerequisites:
Before running the code, ensure you have the following Python packages installed:
- pandas
- numpy
- pgmpy

You can install these packages using pip:
pip install pandas numpy pgmpy

## Dataset:
The dataset data7_heart.csv should be in the same directory as your script. This dataset contains various features related to heart disease such as age, sex, resting blood pressure (trestbps), fasting blood sugar (fbs), exercise induced angina (exang), and other relevant medical information.

## Usage:
1. Ensure all dependencies are installed.
2. Place the dataset (data7_heart.csv) in the same directory as your script.
3. Run the script.
4. The output will be the probability distribution of heart disease given the specified evidence.

## Example Output:
The output will display the probability distribution for the heartdisease variable given the evidence:
+----------------+------------------+
| heartdisease   |   phi(heartdisease) |
+================+==================+
| heartdisease(0) | 0.3              |
+----------------+------------------+
| heartdisease(1) | 0.7              |
+----------------+------------------+
This indicates the probabilities of not having (0) and having (1) heart disease given the evidence provided.

## Notes:
- Evidence: The evidence provided to the query function should match the columns in your dataset.
- Model Structure: The model structure should be designed based on domain knowledge or data analysis.
- Suppressing Warnings: Warnings are suppressed for cleaner output; you may choose to enable them for debugging purposes.

