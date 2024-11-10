# Wine Quality Check Prediction

This project aims to help a wine factory determine the quality of their wine. By analyzing various features in the provided dataset, we predict if a wine's quality is good or not. The goal is to ensure high-quality standards by accurately classifying wines into quality categories.

## Project Overview
The dataset used in this project contains multiple features of wine samples, with the `quality` column serving as the label. The quality values range from 1 to 8, where higher values indicate better quality. For the purpose of prediction, we transformed this multi-class quality rating into a binary classification:
- Quality scores **less than 7** are labeled as **0** (low quality).
- Quality scores **7 and above** are labeled as **1** (high quality).

Using this approach, the model achieved a **93% accuracy** on the test data, making it a reliable tool for predicting wine quality.

## Model and Prediction
The images below illustrate the prediction function developed for this project. When sample input values are provided, the model outputs a binary prediction:
- **1**: The wine quality is good (high quality).
- **0**: The wine quality is not up to standard (low quality).

## Dataset
The dataset used is provided in the repository. It includes features such as acidity, sugar levels, pH, and other chemical properties of the wine that influence its overall quality.

## Getting Started
To use this project:
1. Clone the repository.
2. Install the required dependencies.
3. Run the model on your local system to see the predictions.

## Results
With an accuracy of 93%, this model can assist winemakers in quickly evaluating the quality of their products and ensuring that only the best quality wine reaches the market.

---

Feel free to reach out if you have any questions or suggestions for improvement!
