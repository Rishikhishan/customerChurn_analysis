# Customer Churn Prediction

A machine learning project exploring customer churn prediction using Python and scikit-learn.

## Objective
Identify customers at risk of leaving a hypothetical telecom service and explore how churn predictions could support customer retention.

## Dataset
A synthetic dataset of 5,000 telecom customers created for educational purposes. It does not contain real customer data.

## Tools
- Python
- pandas and NumPy
- Matplotlib and Seaborn
- scikit-learn
- Google Colab

## Approach
1. Data generation and exploratory data analysis
2. Feature selection and preprocessing
3. Logistic Regression baseline
4. Random Forest model comparison
5. Classification threshold evaluation
6. Final model assessment and business interpretation

## Results

| Metric | Test result |

| Accuracy | 59.7% |
| Precision | 40.7% |
| Recall | 84.8% |
| F1-score | 0.550 |
| ROC-AUC | 0.759 |
| Average Precision | 0.552 |

The selected model used a classification threshold of 0.40. It identified 246 of 290 actual churners, while producing 359 false-positive predictions.

## Limitations
- The dataset is synthetic, so results may not generalize to real customers.
- The original test set was used in earlier model and threshold experiments, which limits the independence of the final evaluation.
- Further validation and business cost analysis are needed before deployment.

## How to Run
Open `customerChurn_analysis.ipynb` in Google Colab and run the cells in order.

## Future Work
- Analyze feature importance
- Improve evaluation with a genuinely untouched test set
- Explore the business costs of false positives and missed churners
