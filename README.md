# Heart Disease Classification Model Comparison

Machine learning project comparing Random Forest vs Logistic Regression for heart disease prediction.

## Project Files

- `evaluation_for_small_data.ipynb` - Initial experiment with Cleveland dataset (303 samples)
- `evaluation_for_big_data.ipynb` - Follow-up experiment with large dataset (70,000 samples)

## Research Context

**Initial Experiment** (`evaluation_for_small_data.ipynb`):
- Tested both models on small Cleveland heart disease dataset
- Found no significant performance differences (p ≥ 0.05)
- Results were inconclusive due to limited sample size

**Follow-up Experiment** (`evaluation_for_big_data.ipynb`):
- Conducted with larger dataset to validate initial findings
- Random Forest showed significantly better performance (p < 0.05)
- Included resource monitoring and overfitting analysis

## Key Findings

- **Small dataset (303 samples)**: No significant differences between models (F1: 0.804 vs 0.805, AUC: 0.898 vs 0.897)
- **Large dataset (70,000 samples)**: Random Forest outperforms Logistic Regression (F1: 0.721 vs 0.708, AUC: 0.803 vs 0.784)

## Technologies

Python, Scikit-learn, Pandas, Statistical Testing, Cross-Validation
