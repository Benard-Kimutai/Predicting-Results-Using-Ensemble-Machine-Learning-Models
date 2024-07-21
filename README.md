# Predicting-Results-Using-Ensemble-Machine-Learning-Models

## Background

This project focuses on building and evaluating ensemble machine learning models to predict a target variable (`Result`) using a dataset (`data_9.csv`). The project explores two ensemble methods: Random Forest and Gradient Boosting. Additionally, hyperparameter tuning is performed to optimize the Random Forest model. The performance of both models is compared to determine the best approach for this classification task.

## Dataset

The dataset used in this project is named `data_9.csv` and consists of various features that potentially influence the target variable (`Result`). The dataset has 39 columns with different numerical attributes.

## Project Structure

1. **Loading and Preparing Data**:
   - Load the dataset using pandas.
   - Split the data into training and testing sets.

2. **Building the Initial Random Forest Model**:
   - Train a Random Forest classifier on the training data.
   - Evaluate the model's performance using accuracy, precision, recall, and F1 score.

3. **Hyperparameter Tuning**:
   - Perform Grid Search Cross-Validation to find the best hyperparameters for the Random Forest model.
   - Train and evaluate the optimized Random Forest model.

4. **Building the Gradient Boosting Model**:
   - Train a Gradient Boosting classifier on the training data.
   - Evaluate the model's performance using the same metrics as the Random Forest model.

5. **Comparison of Models**:
   - Compare the performance of the initial Random Forest model, the optimized Random Forest model, and the Gradient Boosting model.

 ## Conclusion
The results show that both the Random Forest and Gradient Boosting models performed excellently on this dataset, achieving perfect scores on the evaluation metrics. Hyperparameter tuning was essential in optimizing the Random Forest model, leading to improved performance. The comparison demonstrates the importance of model selection and tuning in achieving the best predictive performance.

 ## Reflection
Hyperparameter tuning is a critical step in developing machine learning models as it helps in finding the best configuration for the model, leading to improved performance. In this project, Grid Search Cross-Validation was used to find the optimal hyperparameters for the Random Forest model, which resulted in enhanced accuracy, precision, recall, and F1 score. This exercise highlights the necessity of tuning to leverage the full potential of machine learning models.
