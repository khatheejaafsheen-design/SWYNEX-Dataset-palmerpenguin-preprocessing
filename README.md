# # 🐧 Palmer Penguins – Data Preprocessing & Model Improvement

## 📌 Project Overview
This project focuses on exploring, preprocessing, and building machine learning classification models using the **Palmer Penguins Dataset**. It also includes feature engineering, hyperparameter tuning, and cross-validation to evaluate and compare model performance.

## 🎯 Objectives
- Perform Exploratory Data Analysis (EDA).
- Identify and handle missing values.
- Encode categorical features.
- Prepare training and testing datasets.
- Apply feature engineering.
- Perform hyperparameter tuning.
- Evaluate and compare machine learning models.

## 📊 Dataset Description
The Palmer Penguins dataset contains information about three penguin species:
- Adelie
- Chinstrap
- Gentoo

It includes features such as bill length, bill depth, flipper length, body mass, island, and sex.

## 🛠️ Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Google Colab

## ⚙️ Project Workflow

1. **Data Loading:** Load the Palmer Penguins dataset.
2. **EDA:** Explore data using statistical summaries and visualizations.
3. **Data Preprocessing:** Handle missing values using median and mode imputation.
4. **Encoding:** Apply One-Hot Encoding to categorical variables.
5. **Data Splitting:** Split data into training and testing sets using stratification.
6. **Feature Engineering:** Create a new feature called `bill_ratio`.
7. **Model Building:** Train Logistic Regression and Decision Tree classifiers.
8. **Hyperparameter Tuning:** Use GridSearchCV to find suitable model parameters.
9. **Validation:** Apply Stratified 5-Fold Cross Validation.
10. **Model Evaluation:** Compare model performance using accuracy, precision, recall, and F1-score.

## 🤖 Machine Learning Models
- Logistic Regression
- Decision Tree Classifier

## 📈 Final Model Results

| Evaluation Metric | Logistic Regression | Decision Tree |
|---|---:|---:|
| Cross-Validation Accuracy | 99.64% | 98.91% |
| Test Accuracy | 98.55% | 100% |
| Macro Precision | 98% | 100% |
| Macro Recall | 99% | 100% |
| Macro F1-score | 98% | 100% |

## 🏆 Conclusion
Both models achieved excellent classification performance. Decision Tree achieved the highest test accuracy of 100%, while Logistic Regression achieved 99.64% cross-validation accuracy.

Feature engineering and hyperparameter tuning helped analyse model performance and identify suitable model settings.

## 👩‍💻 Author
**Afsheen Khatheeja**

BE Computer Science and Engineering Student

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

Open the machine learning notebook and execute the cells sequentially.

## 💻 Project Execution

1. Load the Palmer Penguins dataset.
2. Perform data preprocessing and feature engineering.
3. Train Logistic Regression and Decision Tree models.
4. Evaluate model performance using classification metrics.
5. Compare both trained models.
6. Predict penguin species using new input data.

## 🔮 Prediction

The trained classification model is intended to predict one of the following penguin species:

- Adelie
- Chinstrap
- Gentoo

Predictions are based on penguin characteristics such as bill measurements, flipper length, body mass, island and sex.

## 📌 Future Improvements

- Develop an interactive prediction interface.
- Experiment with additional classification algorithms.
- Improve model generalization.
- Deploy the model as a web application.

GitHub: [@khatheejaafsheen-design](https://github.com/khatheejaafsheen-design)
