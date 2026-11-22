# 📊 SPREAD LOCATOR
### A Statistical Distribution Analysis Model

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.x-blue?logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/NumPy-Numerical_Computing-013243?logo=numpy" />
  <img src="https://img.shields.io/badge/Pandas-Data_Analysis-150458?logo=pandas" />
  <img src="https://img.shields.io/badge/Matplotlib-Visualization-orange?logo=plotly" />
  <img src="https://img.shields.io/badge/Seaborn-Statistical_Visualization-4C72B0" />
  <img src="https://img.shields.io/badge/Jupyter-Notebook-orange?logo=jupyter" />
  <img src="https://img.shields.io/badge/License-MIT-green.svg" />
</p>

<p align="center">
  <b>Discover the distribution. Measure the spread. Understand the data.</b>
</p>

---

## 🚀 Project Overview

**Spread Locator** is a statistical analysis project designed to explore, identify, and understand the distribution and spread of data through statistical techniques, mathematical foundations, and visual interpretations.

In real-world data analysis, understanding the average alone is not enough. Two datasets can have identical means but completely different distributions, variability, and patterns.

This project explores how statistical measures, probability distributions, Q-Q plots, and data transformations can help uncover the underlying characteristics of a dataset.

The project follows a combination of **theoretical understanding and practical Python implementation**, connecting statistical mathematics with real-world data analysis.

## 🎯 Project Objectives

The primary objectives of this project are:

- Understand the fundamental concepts of probability distributions.
- Analyze the central tendency and variability of data.
- Identify different distribution patterns.
- Measure the spread and dispersion of observations.
- Interpret data using statistical visualizations.
- Understand and construct Q-Q plots.
- Apply statistical transformations to improve distribution characteristics.
- Explore probability functions and their practical applications.
- Derive meaningful statistical insights from an e-commerce dataset.

## 🏢 Business Scenario

Imagine working as a **Data Analyst for an E-Commerce Platform**.

The company collects large amounts of customer and transaction data. However, raw data does not always provide meaningful insights.

Some variables may follow a normal distribution, while others may exhibit skewness, extreme values, or irregular patterns.

Your responsibility as a data analyst is to investigate the dataset and answer questions such as:

1. How is the data distributed?
2. Is the dataset normally distributed?
3. How much variability exists in the observations?
4. Are there any extreme values or outliers?
5. Which probability distribution describes the data?
6. Can statistical transformations improve the distribution?
7. What meaningful conclusions can be derived from statistical analysis?

**The ultimate goal is to transform raw data into statistically meaningful information.**

---

## 🧠 Statistical Concepts Covered

### 1. Measures of Central Tendency

Measures of central tendency identify the central or representative value of a dataset.

| Concept | Mathematical Formula |
|---|---|
| Mean | (bar{x} = {sum(x_i)} / {n}) |
| Median | Middle observation |
| Mode | Most frequently occurring value |

### 2. Measures of Dispersion

Measures of dispersion describe how widely observations are distributed around the center.

| Concept | Mathematical Formula |
|---|---|
| Range | Maximum − Minimum |
| Variance | (sigma^2 = {sum(x_i - mu)^2} / {N}) |
| Standard Deviation | (sigma = {sigma^2}) |
| Interquartile Range | (IQR = Q_3 - Q_1) |
| Coefficient of Variation | (CV = {sigma} / {mu} * times100) |

### 3. Probability Distributions

Probability distributions describe how probabilities are assigned to possible values of a random variable.

**Major distribution types:**

| Distribution | Description |
|---|---|
| Normal Distribution | Symmetrical, bell-shaped distribution |
| Binomial Distribution | Number of successes in fixed independent trials |
| Poisson Distribution | Number of events occurring within a fixed interval |
| Uniform Distribution | Equal probability across a defined interval |
| Exponential Distribution | Models waiting times between events |

### 4. Distribution Shape Analysis

Understand the shape and characteristics of a dataset through:

- **Skewness:** Measures the asymmetry of a distribution.
- **Kurtosis:** Measures the heaviness of distribution tails relative to a normal distribution.
- **Symmetry:** Determines whether the distribution is balanced around its center.
- **Outlier Detection:** Identifies observations that differ significantly from the rest of the dataset.

### 5. Q-Q Plot (Quantile-Quantile Plot)

A Q-Q plot compares the quantiles of an observed dataset against the theoretical quantiles of a selected probability distribution.

It helps determine whether the dataset approximately follows a particular theoretical distribution, especially the normal distribution.

### 6. Statistical Transformations

Data transformations help modify the distribution and improve its statistical characteristics.

Common transformations include:

- Log Transformation
- Square Root Transformation
- Cube Root Transformation
- Box-Cox Transformation
- Yeo-Johnson Transformation

### 7. Probability Functions

Understand the mathematical functions used to calculate probabilities:

- PDF – Probability Density Function
- PMF – Probability Mass Function
- CDF – Cumulative Distribution Function
- PPF – Percent Point Function (Inverse CDF)

---

## 🛠️ Technology Stack

| Technology | Purpose |
|---|---|
| Python | Core programming language |
| NumPy | Numerical and mathematical operations |
| Pandas | Data manipulation and analysis |
| Matplotlib | Data visualization |
| Seaborn | Statistical visualization |
| SciPy | Statistical functions and probability distributions |
| Jupyter Notebook | Interactive practical implementation |
| Microsoft Excel | Dataset storage and management |

---

## 📁 Repository Structure

```text
3.-Spread-Locator/
│
├── Images/
│   └── Project visualizations and screenshots
│
├── Practical_PR_3.ipynb
│   └── Practical statistical implementation
│
├── PR_3.Theory.docx
│   └── Theoretical concepts and explanations
│
├── spread_locator_dataset.xlsx
│   └── Dataset used for statistical analysis
│
├── LICENSE
│   └── MIT License
│
└── README.md
    └── Project documentation
```

---

## ⚙️ Installation & Setup

Follow these steps to run the project locally.

### Step 1: Clone the Repository

```bash
git clone https://github.com/TusharBagle/3.-Spread-Locator.git
```

### Step 2: Navigate to the Project Directory

```bash
cd 3.-Spread-Locator
```

### Step 3: Install Required Libraries

```bash
pip install numpy pandas matplotlib seaborn scipy openpyxl jupyter
```

### Step 4: Launch Jupyter Notebook

```bash
jupyter notebook
```

### Step 5: Execute the Practical Notebook

Open:

```text
Practical_PR_3.ipynb
```

Run the notebook cells sequentially to explore the statistical analysis.

---

## 📊 Project Workflow

The project follows a structured statistical analysis pipeline:

```text
        Raw Dataset
             |
             ▼
       Data Loading
             |
             ▼
      Data Exploration
             |
             ▼
  Descriptive Statistics
             |
             ▼
   Distribution Analysis
             |
             ▼
   Spread & Variability
             |
             ▼
       Q-Q Plots
             |
             ▼
 Statistical Transformations
             |
             ▼
    Probability Analysis
             |
             ▼
   Statistical Insights
```

---

## 📚 Learning Outcomes

After completing this project, you will develop an understanding of:

- How to analyze real-world datasets statistically.
- How to distinguish between different probability distributions.
- How to calculate and interpret measures of dispersion.
- How to identify skewness and kurtosis.
- How to interpret Q-Q plots.
- How to apply mathematical transformations.
- How to work with probability distribution functions.
- How to connect theoretical statistics with practical Python programming.

## 🔮 Future Enhancements

Potential improvements to this project include:

- Automated probability distribution identification.
- Interactive statistical dashboards.
- Automated outlier detection.
- Comparative distribution analysis.
- Advanced goodness-of-fit testing.
- Automated statistical reporting.
- Interactive distribution visualization.

---

## 👨‍💻 Author

**Tushar Bagle**

Aspiring Data Scientist | Python | Statistics | Machine Learning

GitHub: [@TusharBagle](https://github.com/TusharBagle)

Project Repository: [3.-Spread-Locator](https://github.com/TusharBagle/3.-Spread-Locator)

---

## 📜 License

This project is licensed under the **MIT License**.

You are free to use, modify, and distribute this project according to the terms of the license.

See the [LICENSE](LICENSE) file for details.

---

<p align="center">
  <b>📈 Statistics is not just about numbers. It is about discovering the patterns hidden within data.</b>
</p>

<p align="center">
  ⭐ If you find this project useful, consider giving the repository a star!
</p>

--


# Author 
Tushar Bagle
