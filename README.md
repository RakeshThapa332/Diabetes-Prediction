# Diabetes Prediction Using Machine Learning with Python

A Machine Learning classification project that predicts whether an individual is likely to have diabetes based on medical diagnostic measurements.

## Project Overview

Diabetes is a chronic health condition that affects how the body regulates blood glucose levels.

In this project, we develop a Machine Learning model that analyzes medical data and predicts whether a person is likely to have diabetes.

The project uses **Support Vector Machine (SVM)**, a supervised Machine Learning classification algorithm, to classify individuals into two categories:

- **0 – Non-Diabetic:** The individual is classified as not having diabetes.
- **1 – Diabetic:** The individual is classified as having diabetes.

This project demonstrates how Machine Learning can be applied to healthcare-related datasets for predictive analysis.

> **Disclaimer:** This project is for educational purposes only. Its predictions are not medical diagnoses and should not be used as a substitute for professional medical advice.

## Objectives

- Understand and explore the diabetes dataset.
- Perform data preprocessing and statistical analysis.
- Separate input features and target labels.
- Split the dataset into training and testing sets.
- Train an SVM classification model.
- Evaluate the model's predictive performance.
- Predict diabetes outcomes using new input data.

## Technologies Used

- Python
- NumPy
- Pandas
- Scikit-learn
- Matplotlib
- Seaborn
- Jupyter Notebook
- VS Code

## Dataset

This project uses the Pima Diabetes Dataset.

The dataset contains medical diagnostic information used to predict diabetes outcomes.

It includes eight input features and one target variable.

| Feature | Description |
|---|---|
| Pregnancies | Number of times pregnant |
| Glucose | Plasma glucose concentration |
| BloodPressure | Diastolic blood pressure |
| SkinThickness | Triceps skinfold thickness |
| Insulin | 2-hour serum insulin |
| BMI | Body Mass Index |
| DiabetesPedigreeFunction | Diabetes pedigree function |
| Age | Age in years |
| Outcome | Diabetes prediction label (0 or 1) |

## Machine Learning Algorithm

**Support Vector Machine (SVM)**

Support Vector Machine is a supervised Machine Learning algorithm used for classification and regression tasks.

In this project, SVM learns patterns from the medical measurements and identifies a decision boundary to distinguish between diabetic and non-diabetic cases.


## Installation and Setup

### 1. Clone the Repository

```bash
git clone <your-repository-url>
```

### 2. Navigate to the Project Directory

```bash
cd Diabetes-Prediction
```

### 3. Create a Virtual Environment

```bash
python -m venv .venv
```

### 4. Activate the Virtual Environment

For Windows PowerShell:

```powershell
.\.venv\Scripts\Activate.ps1
```

### 5. Install Required Libraries

```bash
pip install numpy pandas matplotlib seaborn scikit-learn jupyter ipykernel
```

### 6. Run the Notebook

Open the `.ipynb` file in VS Code and select the `.venv` Python kernel.

## Learning Outcomes

Through this project, I gained practical experience in:

- Working with healthcare-related datasets.
- Data preprocessing and exploratory data analysis.
- Feature scaling using StandardScaler.
- Implementing Support Vector Machine.
- Training and testing classification models.
- Evaluating Machine Learning performance.
- Making predictions using trained models.

## Future Improvements

- Compare SVM with Logistic Regression, Random Forest, and other classification algorithms.
- Perform hyperparameter tuning.
- Apply cross-validation.
- Improve model evaluation using additional metrics.
- Develop a web-based interface for diabetes risk prediction.
- Investigate class imbalance and data quality.


---

*This project is part of my continuous learning journey in Artificial Intelligence and Machine Learning.*
