# 🚢 Predicting Titanic Survival using Logistic Regression

Welcome! This project analyzes the famous Titanic dataset to predict passenger survival using logistic regression. The workflow covers data loading, cleaning, preprocessing, encoding, and model building.

## 📊 Dataset

The data (`Titanic-Dataset.csv`) contains the following columns:
- PassengerId
- Survived
- Pclass
- Name
- Sex
- Age
- SibSp
- Parch
- Ticket
- Fare
- Cabin
- Embarked

## 🧹 Data Preprocessing

- Dropped columns: `Name`, `PassengerId`, `Ticket`
- Label encoded: `Sex`, `Embarked`
- Filled missing values in `Cabin` with the mode

## 🔍 Initial Data Insights

- Rows: 891
- Columns: 12
- Missing values: `Age`, `Cabin`, `Embarked`
- Data types: int, float, object

## 🏷️ Model

A logistic regression model is used to predict the `Survived` column (0 = did not survive, 1 = survived).

## 🎯 Accuracy

- *Model accuracy:* `XX%` (Update this after you train & evaluate your model!)

## 🚀 Usage

1. Clone this repo
2. Install dependencies (`numpy`, `pandas`, `matplotlib`, `seaborn`, `sklearn`)
3. Place `Titanic-Dataset.csv` in your directory
4. Run `titanic.ipynb` in Jupyter Notebook or Google Colab

## 💡 Next Steps

- Further handle missing values (`Age`, `Embarked`)
- Train, test, and evaluate the logistic regression model
- Add more visualizations 📈

---

Feel free to contribute or suggest improvements! 😃