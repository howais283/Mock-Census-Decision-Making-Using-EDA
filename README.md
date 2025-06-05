# Mock-Census-Analysis-Decision-Support

A data analysis and decision-making project based on a simulated census dataset of an imaginary town. The project uses structured statistical techniques and exploratory data analysis to extract actionable insights and guide urban planning and resource allocation.

---

## 🏙️ Project Overview

This project simulates a real-world scenario where local government analysts must make data-informed decisions using messy, incomplete census data. It involves cleaning, transforming, and analyzing a dataset that captures key demographic, occupational, and housing attributes of over 1,000 residents.

The goal was to identify trends, detect inconsistencies, and propose practical solutions related to education, infrastructure, and public services based on insights from the data.

---

## 📊 Dataset

The dataset contains over **1,000 records** with the following columns:

- **House Number**  
- **Street**  
- **First Name**  
- **Surname**  
- **Age**  
- **Relationship to Head of House**  
- **Marital Status**  
- **Gender**  
- **Occupation**  
- **Infirmity**  
- **Religion**

📁 File location: [`Dataset/census1.csv`](./Dataset/census1.csv)

---

## 🔍 Key Tasks Performed

- Cleaned and standardized 11 columns with missing, incorrect, or inconsistent entries
- Applied logic-based imputation and categorical normalization
- Identified mismatches between variables
- Conducted exploratory data analysis with visualizations
- Performed statistical hypothesis testing to justify resource allocation

---

## 📌 Key Insights

- **Education:** A significant percentage (16.9%) of the population is of school age, supporting investment in new educational infrastructure.
- **Religion:** The dominant religion (32.6% Christian) justifies building new religious facilities.
- **Housing:** Ownership trends and household size indicate areas of potential urban planning support.
- **Occupation & Income:** Segmentation by employment type highlights economic disparity and areas requiring vocational training initiatives.

---

## 📂 Contents

- `notebooks/`: Jupyter notebook with full data processing and analysis
- `dataset/`: Raw census data (`census1.csv`)
- `reports/`: Final report with statistical justification and decision proposals

---

## 🧰 Tools & Libraries

- Python (Pandas, NumPy)
- Matplotlib, Seaborn
- Jupyter Notebook
- Statistical testing (t-tests, chi-squared tests)

---

## 📘 License

This project is for academic and demonstration purposes. Dataset is mock-generated and does not represent real individuals or locations.

