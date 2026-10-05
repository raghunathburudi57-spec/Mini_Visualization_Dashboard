# 🚢 Titanic Survival Visualization Dashboard

## 📌 Project Overview

This project develops a **Mini Visualization Dashboard for Titanic passenger data** using **Python and data visualization techniques**. The objective is to explore the Titanic dataset, perform **data cleaning and preprocessing**, create meaningful derived features, and present important survival patterns through clear and informative visualizations.

The project analyzes passenger information such as **gender, age, passenger class, survival status, family size, fare, and other passenger attributes** to understand how different characteristics are associated with survival outcomes.

## 📊 Dataset

- **Dataset Name:** Titanic Passenger Dataset
- **File Used:** `train.csv`
- **Records:** 891 passengers
- **Original Features:** 12
- **Analysis Type:** Data Analysis & Data Visualization (EDA)

The dataset includes features such as `PassengerId`, `Survived`, `Pclass`, `Name`, `Sex`, `Age`, `SibSp`, `Parch`, `Ticket`, `Fare`, `Cabin`, and `Embarked`.

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook / Google Colab

These libraries are used for data loading, manipulation, numerical operations, statistical analysis, and graphical visualization.

## 📈 Project Tasks

- Imported the required Python libraries
- Loaded the Titanic `train.csv` dataset
- Explored the first records of the dataset
- Examined dataset structure and data types
- Identified missing values
- Performed **data cleaning and preprocessing**
- Filled missing **Age** values using the mean age
- Filled missing **Embarked** values using the most frequent value
- Removed the **Cabin** column because of missing data
- Verified the cleaned dataset for remaining null values
- Created a **Family Size** feature using `SibSp + Parch + 1`
- Created an **Age Group** feature
- Categorized passengers into Child, Teen, Adult, Middle Age, and Senior groups
- Created multiple charts to analyze passenger survival
- Compared survival patterns across different passenger characteristics

## 📊 Data Visualizations

The mini dashboard includes visualizations such as:

- **Survival Count**
- **Survival by Gender**
- **Survival by Passenger Class**
- **Age Distribution**
- **Survival by Age Group**
- **Family Size Distribution**
- **Correlation Heatmap**
- Bar charts
- Count plots
- Histograms
- Statistical visualizations

## 🔍 Key Insights

The dashboard helps analyze important relationships within the Titanic dataset, particularly:

- **Gender and Survival**
- **Passenger Class and Survival**
- **Age and Survival**
- **Age Group and Survival**
- **Family Size and Survival**
- **Relationships between numerical passenger attributes**

The visualizations make it easier to identify patterns and compare survival outcomes across different groups of passengers.

## 📷 Output

The notebook produces:

- Cleaned and processed Titanic data
- Statistical and dataset summaries
- Engineered features such as **Family Size** and **Age Group**
- Survival comparisons
- Multiple graphical visualizations
- Correlation analysis
- A mini visualization dashboard for understanding passenger survival patterns

## 🚀 How to Run

1. Clone or download this repository.
2. Open `Task4_Mini_Visualization_Dashboard.ipynb` in **Jupyter Notebook** or **Google Colab**.
3. Place the `train.csv` dataset in the required working directory.
4. Make sure the required Python libraries are installed.
5. Run all notebook cells sequentially.
6. View the generated analysis, charts, and dashboard visualizations.

## 📂 Repository Contents

- `Task4_Mini_Visualization_Dashboard.ipynb`
- `train.csv`
- `README.md`

## 🎯 Keywords

**Python | Data Analysis | Data Visualization | Exploratory Data Analysis | EDA | Data Cleaning | Data Preprocessing | Titanic Dataset | Titanic Survival Analysis | Pandas | NumPy | Matplotlib | Seaborn | Feature Engineering | Statistical Analysis | Visualization Dashboard | Jupyter Notebook | Google Colab**

## 👨‍💻 Author

**Raghunath Burudi**

## 🙏 Acknowledgement

This project was completed as part of the **Data Analysis with Python Internship at Maincrafts Technology**.
