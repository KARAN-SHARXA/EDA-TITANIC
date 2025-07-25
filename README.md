# Titanic Dataset - Exploratory Data Analysis (EDA)

This project involves an in-depth **Exploratory Data Analysis (EDA)** of the Titanic dataset. The goal is to understand the dataset's structure, identify key patterns, and generate insights that can be useful for further modeling or business understanding.

## 🔍 Objectives

- Understand different types of data: **Numerical**, **Categorical**, and **Mixed**
- Perform **Bivariate Analysis** to examine relationships between variables
- Apply **Feature Engineering** to create useful new features
- Prepare the dataset for potential machine learning models

---

## 📁 Dataset

The dataset used is the **Titanic Dataset** from Kaggle or other public sources. It includes features like:

- PassengerId, Name, Sex, Age, SibSp, Parch, Ticket, Fare, Cabin, Embarked, Survived, etc.

---

## 🧪 Data Types Analyzed

### 1. **Numerical Features**
   - Examples: `Age`, `Fare`, `SibSp`, `Parch`
   - Analysis: Distribution plots, histograms, boxplots, missing values

### 2. **Categorical Features**
   - Examples: `Sex`, `Embarked`, `Pclass`
   - Analysis: Count plots, pie charts, value_counts, missing value handling

### 3. **Mixed/Combined Types**
   - Some columns like `Cabin` and `Ticket` have both numeric and alphabetic components.
   - Handled by cleaning, splitting, or encoding based on context.

---

## 🔗 Bivariate Analysis

Studied the relationship between two variables across all combinations:

### - **Numerical vs Numerical**
   - Example: `Age` vs `Fare`
   - Tools: Scatter plots, correlation heatmaps

### - **Categorical vs Categorical**
   - Example: `Sex` vs `Survived`, `Embarked` vs `Pclass`
   - Tools: Groupby tables, stacked bar charts, crosstabs

### - **Categorical vs Numerical**
   - Example: `Pclass` vs `Fare`, `Survived` vs `Age`
   - Tools: Boxplots, violin plots, bar plots

---

## 🧠 Feature Engineering

Created several new useful columns to enrich the dataset:

- `Family_Size` = `SibSp` + `Parch` + 1  
- `Family_Type`: Categorized family size into:
  - `Single`: Family_Size = 1
  - `Small`: Family_Size between 2 and 4
  - `Large`: Family_Size > 4
- `Fare_Per_Person` = `Fare` / `Family_Size`

These new features help in uncovering deeper relationships and enhance the model’s predictive power.

---

## 📈 Tools Used

- Python (Pandas, NumPy, Matplotlib, Seaborn)
- Jupyter Notebook

---

## 📌 Conclusion

This EDA provided clear insights into the structure of the Titanic dataset. We explored key relationships between variables, handled different data types, and created new meaningful features that could improve future predictions.

---

## 📎 Author

**Karan Sharma**  
_Data Science Learner | EDA Enthusiast_

---

