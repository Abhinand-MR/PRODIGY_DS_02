# PRODIGY_DS_02
# Task 02 – Exploratory Data Analysis on Titanic Dataset

## 🎯 Objective
Perform data cleaning and exploratory data analysis (EDA) on the Titanic dataset to understand survival patterns and identify relationships between features such as age, gender, class, and more.

## 📎 Dataset
- Source: [Kaggle Titanic: Machine Learning from Disaster](https://www.kaggle.com/competitions/titanic/data)
- Data includes passenger information like age, sex, fare, class, embarked location, and survival status.

## 🧰 Tools & Libraries Used
- Python
- Pandas
- NumPy
- Seaborn
- Matplotlib

## ⚙️ Task Workflow

1. **Data Loading**
   - Loaded the dataset into a Pandas DataFrame using `read_csv`.

2. **Data Cleaning**
   - Identified and handled missing values (`Age`, `Cabin`, `Embarked`).
   - Converted categorical variables like `Sex` and `Embarked` into numerical formats.
   - Removed unnecessary columns such as `PassengerId`, `Ticket`, and `Cabin` for initial analysis.

3. **Exploratory Data Analysis**
   - Univariate Analysis:
     - Plotted distributions of `Age`, `Fare`, `Pclass`, and `Survived`.
   - Bivariate Analysis:
     - Compared survival rates across `Sex`, `Pclass`, `Embarked`, and `Age` groups.
   - Correlation Analysis:
     - Generated a heatmap to identify relationships between numerical features.

4. **Visualization**
   - Used Seaborn and Matplotlib to create:
     - Count plots for `Survived` vs `Sex`, `Pclass`, `Embarked`
     - Histograms and KDE plots for `Age` and `Fare`
     - Heatmaps for feature correlation

## 📊 Output

- Survival rate comparisons by gender and class
- Age and fare distribution among passengers
- Correlation heatmap showing relationships between features

## 📷 Sample Visuals
*(Optional: Add screenshots like survival_by_gender.png, correlation_heatmap.png)*

## ✅ Learnings

- How to clean and preprocess real-world datasets with missing and categorical data
- Performed in-depth exploratory analysis to derive patterns
- Improved understanding of visual storytelling using Seaborn
- Gained insights on what factors contributed to higher survival chances

## 📂 Folder Structure

