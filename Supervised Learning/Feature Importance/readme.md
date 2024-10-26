# Feature Importance

**Feature importance** is the technique of assigning a score to input features based on their usefulness in predicting a target variable. This helps in identifying which features have the greatest impact on the model's performance, leading to more efficient models and a better understanding of underlying relationships in the data.

## Common Methods for Determining Feature Importance

- **Tree-based methods**: Assign importance scores based on the feature splits in decision trees, e.g., in Random Forest or Gradient Boosting.
- **Coefficient-based methods (Regression)**: Use the absolute values of coefficients in linear models to determine feature significance.
- **SHAP (SHapley Additive exPlanations) values**: Based on cooperative game theory, SHAP values show the contribution of each feature to the prediction in a more interpretable way.

---
