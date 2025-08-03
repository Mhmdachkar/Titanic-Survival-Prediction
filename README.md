# 🚢 Titanic Survival Prediction - Internship Project

A comprehensive machine learning project developed during my internship that predicts passenger survival on the Titanic using historical data. This project demonstrates the complete ML pipeline from data exploration to model deployment as part of my professional development program.

## 🎯 Project Overview

This internship project uses the famous Kaggle Titanic dataset to predict whether a passenger survived or not based on features like:

- Passenger class
- Gender
- Age
- Number of siblings/spouses aboard
- Number of parents/children aboard
- Ticket fare
- Port of embarkation

## 📊 Dataset

The dataset contains information about 891 passengers from the Titanic. Key features include:

| Feature | Description | Type |
|---------|------------|------|
| Pclass | Passenger Class (1st, 2nd, 3rd) | Categorical |
| Sex | Gender | Categorical |
| Age | Age in years | Numerical |
| SibSp | Number of siblings/spouses aboard | Numerical |
| Parch | Number of parents/children aboard | Numerical |
| Fare | Passenger fare | Numerical |
| Embarked | Port of embarkation (C, Q, S) | Categorical |

## 🚀 Setup and Usage

### Prerequisites
- Python 3.7+
- Jupyter Notebook or JupyterLab
- Required libraries: pandas, numpy, matplotlib, seaborn, scikit-learn

### Usage
1. Clone or download this repository
2. Navigate to the project directory
3. Open `notebooks/Titanic_passanger_survival.ipynb` in Jupyter Notebook
4. Run all cells to see the complete analysis and results

### Dataset
The dataset files are included in the `data/` folder:
- `train.csv` - Training data with survival labels
- `test.csv` - Test data for predictions
- `gender_submission.csv` - Sample submission format

## 📁 Project Structure

```
titanic-survival-prediction/
│
├── notebooks/                     # Jupyter notebooks
│   └── Titanic_passanger_survival.ipynb
│
├── data/                          # Dataset files
│   ├── train.csv
│   ├── test.csv
│   └── gender_submission.csv
│
└── README.md                      # This file
```

## 🔧 Analysis Features

The Jupyter notebook includes:

### Data Exploration & Preprocessing
- ✅ Comprehensive data exploration and visualization
- ✅ Missing value analysis and imputation strategies
- ✅ Feature engineering (family size, titles, age groups)
- ✅ Categorical encoding and feature scaling

### Machine Learning Models
- 🤖 Multiple classification algorithms implementation
- 📈 Model comparison and evaluation
- 🌳 Feature importance analysis

### Visualization & Insights
- 📊 Data distribution plots and survival analysis
- 🎯 Model performance metrics and confusion matrices
- 📈 Feature correlation and importance visualizations

## 📈 Key Findings

The analysis reveals several important insights about Titanic passenger survival:

- **Gender Impact**: Female passengers had significantly higher survival rates
- **Class Matters**: First-class passengers had better survival chances
- **Age Factor**: Children and younger passengers were more likely to survive
- **Family Size**: Passengers with small families had better survival rates
- **Fare Correlation**: Higher ticket fares correlated with better survival odds

Detailed results and model performance metrics are available in the Jupyter notebook.

## 📚 Learning Outcomes

Through this internship project, I gained hands-on experience with:

- 🔍 Exploratory Data Analysis (EDA)
- 🛠️ Data Preprocessing and feature engineering
- 🤖 Machine Learning model training and tuning
- 📊 Model Evaluation using multiple metrics
- 🎯 Prediction on new data
- 📈 Visualization of results and insights

## 🙏 Acknowledgments

- My internship supervisor and team for guidance and support
- The company for providing this learning opportunity
- Kaggle for providing the dataset
- The data science community for resources and best practices

---

*This project was completed as part of my internship program, demonstrating practical application of machine learning concepts in a professional development context.*
