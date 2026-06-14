# 🚢 Titanic Data Analysis Using Python

> Exploratory data analysis of the Titanic passenger dataset — uncovering the patterns and factors that determined who survived the tragedy of April 15, 1912.

---

## 📌 Table of Contents

- [Overview](#overview)
- [Project Structure](#project-structure)
- [Dataset](#dataset)
- [Key Questions Explored](#key-questions-explored)
- [Technologies Used](#technologies-used)
- [Getting Started](#getting-started)
- [Analysis Workflow](#analysis-workflow)
- [Key Findings](#key-findings)
- [Author](#author)

---

## Overview

The sinking of the RMS Titanic is one of the most infamous maritime disasters in history. On April 15, 1912, during her maiden voyage, the Titanic sank after colliding with an iceberg — resulting in the deaths of over 1,500 of the 2,224 passengers and crew aboard.

This project performs in-depth **Exploratory Data Analysis (EDA)** on the Titanic passenger dataset using Python. The goal is to clean, visualize, and statistically explore the data to identify which factors — such as age, gender, ticket class, and family size — most significantly influenced a passenger's chance of survival.

---

## Project Structure

```
Titanic-Data-Analysis-Using-Python/
│
├── Dataset/
│   └── Titanic-Dataset.xls        # Raw Titanic passenger dataset
│
├── Project/
│   └── Titanic Project.ipynb      # Main Jupyter Notebook with full analysis
│
└── README.md                      # Project documentation
```

---

## Dataset

The dataset (`Titanic-Dataset.xls`) contains information on passengers aboard the RMS Titanic and includes the following key features:

| Column | Description |
|---|---|
| `PassengerId` | Unique identifier for each passenger |
| `Survived` | Survival status (0 = No, 1 = Yes) |
| `Pclass` | Ticket class (1 = 1st, 2 = 2nd, 3 = 3rd) |
| `Name` | Full name of the passenger |
| `Sex` | Gender of the passenger |
| `Age` | Age in years |
| `SibSp` | Number of siblings/spouses aboard |
| `Parch` | Number of parents/children aboard |
| `Ticket` | Ticket number |
| `Fare` | Passenger fare |
| `Cabin` | Cabin number |
| `Embarked` | Port of embarkation (C = Cherbourg, Q = Queenstown, S = Southampton) |

---

## Key Questions Explored

- What was the overall survival rate among passengers?
- How did **gender** affect survival chances?
- Did **passenger class (Pclass)** play a role in survival?
- How did **age** correlate with survival?
- Did travelling with **family members** (SibSp / Parch) improve survival odds?
- What was the relationship between **fare paid** and survival?
- Which **port of embarkation** had the highest survival rate?

---

## Technologies Used

| Tool | Purpose |
|---|---|
| **Python 3.x** | Core programming language |
| **Jupyter Notebook** | Interactive analysis environment |
| **Pandas** | Data manipulation and cleaning |
| **NumPy** | Numerical computation |
| **Matplotlib** | Static data visualization |
| **Seaborn** | Statistical data visualization |

---

## Getting Started

### Prerequisites

Make sure you have Python 3.x and pip installed.

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/Muhammad-Musharraf/Titanic-Data-Analysis-Using-Python.git
   cd Titanic-Data-Analysis-Using-Python
   ```

2. **Install required libraries**
   ```bash
   pip install pandas numpy matplotlib seaborn jupyter openpyxl
   ```

3. **Launch Jupyter Notebook**
   ```bash
   jupyter notebook
   ```

4. **Open the notebook**  
   Navigate to `Project/Titanic Project.ipynb` and run the cells.

---

## Analysis Workflow

The notebook follows a structured EDA pipeline:

1. **Data Loading** — Importing the `.xls` dataset using Pandas
2. **Data Inspection** — Reviewing shape, data types, and summary statistics
3. **Data Cleaning** — Handling missing values (Age, Cabin, Embarked) and correcting data types
4. **Feature Engineering** — Creating derived features (e.g., family size, age groups)
5. **Univariate Analysis** — Exploring individual variable distributions
6. **Bivariate Analysis** — Examining relationships between variables and survival
7. **Multivariate Analysis** — Combined factor analysis using heatmaps and grouped visuals
8. **Statistical Insights** — Drawing conclusions from visual and numerical patterns

---

## Key Findings

- **Gender**: Female passengers had a significantly higher survival rate than male passengers, consistent with the "women and children first" evacuation protocol.
- **Passenger Class**: First-class passengers were far more likely to survive than those in second or third class, highlighting socioeconomic disparities in access to lifeboats.
- **Age**: Children had higher survival rates; elderly passengers had lower survival chances on average.
- **Family Size**: Passengers travelling with small families tended to survive more than solo travelers or those in very large groups.
- **Fare**: Higher ticket fares (correlated with first-class travel) were associated with better survival outcomes.
- **Embarkation Port**: Passengers who boarded at Cherbourg (C) had a notably higher survival rate than those from Southampton or Queenstown.

---

## Author

**Muhammad Musharraf**  
📂 GitHub: [@Muhammad-Musharraf](https://github.com/Muhammad-Musharraf)

---

> *"In the end, the data tells a story — not just of statistics, but of the human realities aboard the Titanic."*
