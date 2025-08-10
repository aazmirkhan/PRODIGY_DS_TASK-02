Titanic Dataset - Exploratory Data Analysis

This project was completed as part of my internship at **Prodigy InfoTech**. The objective was to perform **Exploratory Data Analysis (EDA)** on the Titanic dataset, uncover patterns, and prepare a final cleaned dataset for further use.

📌 Project Overview

The notebook explores the Titanic dataset to understand relationships between passenger attributes and survival rates. It includes:

* Data cleaning and preprocessing
* Exploring relationships & patterns in the Titanic dataset
* Visualizations to highlight key patterns
* Statistical observations from the analysis
* Export of a processed dataset for evaluation

📂 About the Dataset

The **Titanic dataset** contains demographic and travel information for passengers aboard the RMS Titanic, which sank in 1912.

* **Target Variable:** `Survived` (0 = No, 1 = Yes)
* **Key Features:** Passenger class, gender, age, number of siblings/spouses, number of parents/children, ticket fare, and embarkation port.
* Dataset Source: [Kaggle Titanic Dataset](https://www.kaggle.com/c/titanic)

🛠 Tools & Libraries Used

* **Python**
* **Pandas** – Data manipulation
* **Matplotlib & Seaborn** – Data visualization
* **NumPy** – Numerical operations

📊 Key Insights from Analysis

1. **Gender** played a major role — females had a significantly higher survival rate than males.
2. **Passenger Class (Pclass)** strongly influenced survival — 1st class passengers survived more often than 3rd class passengers.
3. **Age** mattered — children had higher survival rates.
4. **Fare** was generally higher for survivors, suggesting better access to lifeboats.
5. **Correlation heatmap** showed strong correlation between Fare and Pclass, but Age had weaker direct correlation with survival.

