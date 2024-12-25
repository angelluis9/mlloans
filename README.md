# Loan Default Prediction

## Project Overview

This repository contains a machine learning project aimed at predicting loan default probabilities. The project utilizes a Voting Classifier that combines the strengths of Random Forest and XGBoost models to achieve highly accurate predictions. The results show exceptional performance, making the model ready for practical applications in finance and banking.

## Key Features

- **Machine Learning Models**: Implementation of Random Forest and XGBoost.
- **Ensemble Learning**: A Voting Classifier is used to combine the predictions of the individual models.
- **High Accuracy**: The final model achieves an accuracy of **99.53%**, with only **4 misclassifications out of 854 predictions**.

## Dataset

The dataset includes features relevant to predicting loan defaults, such as:

- Loan amount
- Income
- Credit history
- Loan term

## Notebook Structure

### 1. Data Preprocessing

- Missing values handling
- Feature engineering
- Data normalization and splitting

### 2. Model Development

- Training and evaluation of Random Forest and XGBoost models.
- Implementation of the Voting Classifier for improved accuracy.

### 3. Model Evaluation

- Calculation of accuracy and visualization of confusion matrices.
- Insights into misclassification cases.

## Results

The Voting Classifier significantly outperforms individual models in terms of accuracy and robustness. A detailed confusion matrix is provided in the notebook for further analysis.

## Technologies Used

- Python
- Scikit-learn
- XGBoost

## Conclusion

This project demonstrates the power of ensemble learning in achieving high accuracy for predicting loan defaults. It is well-suited for deployment in financial institutions seeking to minimize risk and improve decision-making processes.

---

Feel free to contribute by submitting issues or pull requests. Happy coding!

