# Breast-Cancer-classification-using-Logistic-regression-machine-learning-model
This project builds a Logistic Regression model to classify breast tumors as malignant or benign based on 30 features from the Breast Cancer Wisconsin dataset. The model learns the relationship between these features and the tumor type, then predicts the class for new cases.It achieved an accuracy of 94%.

# Dataset

- 569 samples
- 30 diagnostic features
- Target Classes
    0 = Malignant
    1 = Benign
  
## Technologies

- Python
- NumPy
- Pandas
- Scikit-learn

## Workflow

1. Load the dataset.
2. Explore and prepare the data.
3. Split the data into training (80%) and testing (20%).
4. Train a Logistic Regression model.
5. Evaluate model accuracy.
6. Predict the diagnosis for new patient data.

## Requirements

```bash
pip install numpy pandas scikit-learn
```

## Run

```bash
python breast_cancer.py
```

## Output

The model predicts whether the tumor is:

- Malignant
- **Benign**
