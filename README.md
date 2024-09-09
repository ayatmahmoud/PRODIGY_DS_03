# Decision Tree Classifier for Predicting Customer Purchases

**Task 03: Build a Decision Tree Classifier**  
This project focuses on building a decision tree classifier to predict whether a customer will purchase a product or service based on their demographic and behavioral data. The dataset used for this task is sourced from the UCI Machine Learning Repository: [Bank Marketing Dataset](https://archive.ics.uci.edu/ml/datasets/Bank+Marketing).

## Table of Contents

- [Dataset](#dataset)
- [Project Overview](#project-overview)
- [Model](#model)
- [Installation](#installation)
- [Usage](#usage)
- [License](#license)

## Dataset

The dataset contains information about a direct marketing campaign by a Portuguese bank, where the goal is to predict if a client will subscribe to a term deposit (the target variable). You can download the dataset from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Bank+Marketing).

Key features of the dataset include:
- **Demographic data**: age, job, marital status, education level, etc.
- **Behavioral data**: number of contacts, previous campaigns, duration of the current call, etc.

## Project Overview

In this project, we built a **Decision Tree Classifier** to predict customer purchases. The classifier is trained and evaluated using the Bank Marketing dataset.

### Steps:
1. **Data Preprocessing**: Handle missing values, encode categorical variables, and scale features.
2. **Model Training**: Train the Decision Tree Classifier using the preprocessed data.
3. **Evaluation**: Evaluate model performance using accuracy, precision, recall, and other metrics.
4. **Visualization**: Visualize the decision tree and feature importance.

## Model

The decision tree model is built using the **scikit-learn** library. It includes:
- Training the model on the dataset.
- Hyperparameter tuning.
- Evaluating model performance.

Dependencies include:
- pandas
- numpy
- scikit-learn
- matplotlib
- seaborn

## License

This project is licensed under the MIT License - see the LICENSE file for details.
