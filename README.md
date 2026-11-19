# 🐧 Palmer Penguins – Data Preprocessing & Model Improvement

## 📌 Project Overview

This project focuses on exploring, preprocessing, and building machine learning classification models using the **Palmer Penguins Dataset**.

The project covers the complete machine learning workflow, including Exploratory Data Analysis (EDA), data preprocessing, feature engineering, model training, hyperparameter tuning, cross-validation, model evaluation, and prediction.

Two classification algorithms, Logistic Regression and Decision Tree, are implemented and compared to identify their performance.

## 🎯 Project Objectives

- Perform Exploratory Data Analysis (EDA).
- Identify and handle missing values.
- Encode categorical features.
- Prepare training and testing datasets.
- Apply feature engineering.
- Train multiple machine learning models.
- Perform hyperparameter tuning using GridSearchCV.
- Evaluate models using classification metrics.
- Save trained models for future predictions.

## 📊 Dataset Description

The Palmer Penguins Dataset contains information about three penguin species:

- Adelie
- Chinstrap
- Gentoo

**Dataset Features:**

| Feature | Description |
|---|---|
| bill_length_mm | Bill length in millimeters |
| bill_depth_mm | Bill depth in millimeters |
| flipper_length_mm | Flipper length in millimeters |
| body_mass_g | Body mass in grams |
| island | Island where the penguin was observed |
| sex | Penguin's sex |
| species | Target variable (penguin species) |

## 🛠️ Technologies Used

- **Python** – Programming language
- **Pandas** – Data manipulation and analysis
- **NumPy** – Numerical operations
- **Matplotlib** – Data visualization
- **Seaborn** – Statistical visualization
- **Scikit-learn** – Machine learning algorithms and evaluation
- **Joblib** – Saving and loading trained models
- **Google Colab** – Development environment
- **Jupyter Notebook** – Interactive coding environment

## ⚙️ Project Workflow

The project follows these major steps:

1. **Data Loading:** Load the Palmer Penguins dataset.
2. **Exploratory Data Analysis:** Understand the dataset using statistical summaries and visualizations.
3. **Data Preprocessing:** Identify and handle missing values using median and mode imputation.
4. **Categorical Encoding:** Convert categorical features using One-Hot Encoding.
5. **Data Splitting:** Split the dataset into training and testing sets using stratified sampling.
6. **Feature Engineering:** Create a new feature called `bill_ratio` using bill length and bill depth.
7. **Model Training:** Train Logistic Regression and Decision Tree classifiers.
8. **Hyperparameter Tuning:** Apply GridSearchCV to identify suitable model parameters.
9. **Cross Validation:** Use Stratified 5-Fold Cross Validation.
10. **Model Evaluation:** Compare model performance using accuracy, precision, recall, and F1-score.
11. **Model Saving:** Save the best trained models using Joblib.
12. **Prediction:** Use the saved models to predict the species of a new penguin.

## 🤖 Machine Learning Models

Two classification algorithms were implemented:

### 1. Logistic Regression
A supervised classification algorithm used to predict the penguin species based on the input features.

### 2. Decision Tree Classifier
A tree-based classification algorithm that makes predictions using feature-based decision rules.

Both models were optimized using GridSearchCV.

## 📈 Final Model Evaluation Results

The following table shows the final performance of both models.

| Evaluation Metric | Logistic Regression | Decision Tree |
|---|---:|---:|
| Cross-Validation Accuracy | 99.64% | 98.91% |
| Test Accuracy | 98.55% | 100% |
| Macro Precision | 98% | 100% |
| Macro Recall | 99% | 100% |
| Macro F1-Score | 98% | 100% |

### 🏆 Best Performing Model

The Decision Tree classifier achieved the highest test accuracy of **100%**, while Logistic Regression achieved a cross-validation accuracy of **99.64%**.

Both models demonstrated excellent classification performance on the evaluation data.

## 💾 Saved Machine Learning Models

The best tuned models were saved using the Joblib library.

- `logistic_regression.pkl`
- `decision_tree.pkl`

These files contain the trained machine learning pipelines and can be loaded for future predictions.

## 🔍 Model Prediction

Both saved models were successfully loaded and tested using new penguin input data.

**Sample Prediction Input:**

| Feature | Input Value |
|---|---|
| Bill Length | 45.0 mm |
| Bill Depth | 14.5 mm |
| Flipper Length | 215 mm |
| Body Mass | 5000 g |
| Island | Biscoe |
| Sex | Male |

**Prediction Results:**

| Model | Predicted Species |
|---|---|
| Logistic Regression | Gentoo |
| Decision Tree | Gentoo |

Both models successfully predicted **Gentoo** for the given sample input.

## ⚙️ Installation and Setup

Follow these steps to run the project on your local machine.

### 1. Clone the Repository

```bash
git clone https://github.com/khatheejaafsheen-design/SWYNEX-Dataset-palmerpenguin-preprocessing.git
```

### 2. Navigate to the Project Folder

```bash
cd SWYNEX-Dataset-palmerpenguin-preprocessing
```

### 3. Install Required Libraries

```bash
pip install -r requirements.txt
```

### 4. Run the Jupyter Notebook

```bash
jupyter notebook
```

Open the project notebook and execute the cells sequentially.

## 💻 Project Execution

To execute the project:

1. Open the Jupyter Notebook in Google Colab or Jupyter Notebook.
2. Load the Palmer Penguins dataset.
3. Perform data exploration and preprocessing.
4. Apply feature engineering.
5. Train Logistic Regression and Decision Tree models.
6. Perform hyperparameter tuning and cross-validation.
7. Evaluate and compare model performance.
8. Save the trained models using Joblib.
9. Load the saved models and perform predictions.

## 🔮 Future Improvements

- Develop an interactive penguin species prediction interface.
- Experiment with additional classification algorithms.
- Improve model generalization using additional validation techniques.
- Deploy the trained model as a web application.
- Create a user-friendly interface for entering penguin details and viewing predictions.

## 👩‍💻 Author

**Afsheen Khatheeja**

BE Computer Science and Engineering Student

**GitHub:** [@khatheejaafsheen-design](https://github.com/khatheejaafsheen-design)

---

⭐ *This project was developed as part of a hands-on machine learning project to gain practical experience in data preprocessing, model building, evaluation, and prediction.*
