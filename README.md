# 🌌 Stellar & Exoplanet Analysis

## 📌 Project Overview

This project focuses on **Stellar and Exoplanet Data Analysis**, exploring stellar systems and their associated planetary characteristics to uncover meaningful patterns, relationships, and insights.

The project follows an end-to-end data science workflow, starting with data exploration and cleaning, followed by feature engineering, machine learning model development, and interactive data visualization.

The main objective is to analyze exoplanet-hosting systems, understand their characteristics, and build a machine learning classification model to predict the number of planets in a stellar system.

---

## 🎯 Project Objectives

- Explore and understand stellar and exoplanet datasets.
- Perform Exploratory Data Analysis (EDA) to identify patterns, distributions, and relationships.
- Clean and preprocess the raw datasets.
- Perform feature extraction and feature engineering to improve data quality and model performance.
- Build a classification model using `sy_pnum` as the target variable.
- Address class imbalance in the classification dataset.
- Develop an interactive Power BI dashboard to present key findings and insights.

---

## 📂 Project Structure

The project is organized into three main directories and two additional files:

```text
Stellar-Analysis/
│
├── Data/
│   ├── STELLARHOSTS_2025.02.03_06.11.17.csv
│   ├── cleaned_exoplanet_data.csv
│   ├── meta_data.csv
│   └── modeling_data.csv
│
├── Notebooks/
│   ├── EDA.ipynb
│   ├── Cleaning.ipynb
│   ├── Feature_eng.ipynb
│   └── model_building.ipynb
│
├── Dashboard/
│   └── dashboard.pbix
│
├── requirements.txt
│
└── README.md
```

---

## 📊 Dataset Description

The `Data/` directory contains the datasets used throughout the project.

| File | Description |
|---|---|
| `STELLARHOSTS_2025.02.03_06.11.17.csv` | Original stellar host dataset containing the raw data used for analysis. |
| `cleaned_exoplanet_data.csv` | Cleaned and preprocessed dataset prepared for further analysis. |
| `meta_data.csv` | Metadata containing additional information about the dataset and its variables. |
| `modeling_data.csv` | Final dataset prepared for machine learning model development. |

---

## 📓 Notebooks Description

The `Notebooks/` directory contains the complete data science workflow.

### 1. EDA.ipynb – Exploratory Data Analysis

This notebook focuses on understanding the dataset and discovering meaningful insights.

Main activities:
- Understanding dataset dimensions and structure.
- Analyzing data types and statistical summaries.
- Identifying missing values and duplicates.
- Exploring feature distributions.
- Analyzing correlations and relationships between variables.
- Visualizing important patterns and trends.

### 2. Cleaning.ipynb – Data Cleaning

This notebook focuses on preparing the raw data for analysis and modeling.

Main activities:
- Handling missing values.
- Removing duplicate records.
- Correcting data types.
- Handling inconsistent and invalid values.
- Preparing a clean dataset for feature engineering.

### 3. Feature_eng.ipynb – Feature Engineering

This notebook focuses on extracting and creating useful features to improve the quality of the dataset.

Main activities:
- Feature extraction.
- Creating new meaningful variables.
- Selecting relevant features.
- Removing unnecessary columns.
- Preparing the final modeling dataset.

### 4. model_building.ipynb – Machine Learning Model

This notebook focuses on developing a classification model to predict the number of planets in a stellar system.

**Target Variable:** `sy_pnum`

Main activities:
- Preparing training and testing datasets.
- Selecting relevant features.
- Building classification models.
- Addressing class imbalance.
- Evaluating model performance.
- Comparing classification metrics and results.

---

## 📈 Power BI Dashboard

The `Dashboard/` directory contains the interactive Power BI dashboard.

**Dashboard File:** `dashboard.pbix`

The dashboard provides a visual representation of the analysis and helps communicate important findings through interactive visualizations.

To access the dashboard:

1. Navigate to the `Dashboard/` directory.
2. Open `dashboard.pbix` using Microsoft Power BI Desktop.
3. Explore the available visualizations and interactive reports.

---

## 🛠️ Technologies & Tools

The project uses the following technologies:

| Technology | Purpose |
|---|---|
| Python | Data analysis and machine learning |
| Pandas | Data manipulation and preprocessing |
| NumPy | Numerical computations |
| Matplotlib | Data visualization |
| Seaborn | Statistical data visualization |
| Scikit-learn | Machine learning and model evaluation |
| Jupyter Notebook | Interactive development and analysis |
| Power BI | Interactive dashboard development |

---

## ⚙️ Installation & Setup

Follow these steps to run the project locally.

### 1. Clone the Repository

```bash
git clone <repository-url>
```

### 2. Navigate to the Project Directory

```bash
cd Stellar-Analysis
```

### 3. Create a Virtual Environment (Optional)

```bash
python -m venv venv
```

Activate the environment:

**Windows:**
```bash
venv\Scripts\activate
```

**Linux / macOS:**
```bash
source venv/bin/activate
```

### 4. Install Dependencies

Install the required Python libraries using:

```bash
pip install -r requirements.txt
```

### 5. Run Jupyter Notebook

```bash
jupyter notebook
```

Navigate to the `Notebooks/` directory and execute the notebooks in the following order:

1. `EDA.ipynb`
2. `Cleaning.ipynb`
3. `Feature_eng.ipynb`
4. `model_building.ipynb`

---

## 🔄 Project Workflow

The project follows this general workflow:

```text
Raw Dataset
     |
     ▼
Exploratory Data Analysis (EDA)
     |
     ▼
Data Cleaning & Preprocessing
     |
     ▼
Feature Engineering & Extraction
     |
     ▼
Final Modeling Dataset
     |
     ▼
Machine Learning Model Building
     |
     ▼
Model Evaluation
     |
     ▼
Power BI Dashboard & Insights
```

---

## 📌 Future Improvements

Potential future improvements include:

- Experimenting with additional classification algorithms.
- Improving model performance through hyperparameter tuning.
- Exploring advanced techniques for handling imbalanced datasets.
- Applying feature selection techniques.
- Adding more interactive visualizations to the Power BI dashboard.
- Incorporating additional astronomical datasets for deeper analysis.

---

## 👨‍💻 Author

**Ahmed Sayed**

Data Science & Machine Learning Enthusiast

---

## 📄 License

This project is intended for educational and analytical purposes.