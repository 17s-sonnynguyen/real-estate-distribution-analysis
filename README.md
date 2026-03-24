# Real Estate Distribution Analysis

## 📌 Project Overview

This project applies **probability and statistical distribution concepts** to a real estate dataset.
The goal is to understand how housing-related variables—especially price—are distributed and how they behave under different conditions.

Through this analysis, we explore both **empirical data distributions** and **theoretical probability models**, bridging the gap between data science and probability theory.

---

## 🎯 Objectives

* Analyze the distribution of housing prices and key features
* Identify skewness, variability, and outliers
* Compare empirical distributions with theoretical models (Normal vs Log-Normal)
* Explore conditional distributions based on property characteristics
* Apply probability concepts such as:

  * Expected value (mean)
  * Variance and standard deviation
  * Probability density functions (PDF)
  * Conditional probability

---

## 📂 Dataset

The dataset contains 100 observations with the following variables:

* **price** → Property price (continuous)
* **size** → Property size (continuous)
* **year** → Year of construction (discrete)
* **view** → Property view category (categorical)

---

## 🧪 Methodology

### 1. Data Loading & Overview

* Inspected dataset structure and data types
* Verified absence of missing values

### 2. Data Cleaning & Preprocessing

* Removed duplicates
* Converted categorical variables
* Standardized column formats

### 3. Exploratory Data Analysis (EDA)

* Histograms and KDE plots
* Boxplots for outlier detection
* Scatter plots for relationships
* Correlation analysis

### 4. Distribution Analysis

* Analyzed distribution shapes of variables
* Computed skewness and kurtosis
* Identified non-normal behavior in price

### 5. Statistical Measures

* Mean, median, variance, standard deviation
* Coefficient of variation
* Quantile-based probability interpretation

### 6. Conditional Distributions

* Compared price distributions across `view` categories
* Analyzed conditional expectations:

  * E[Price | View]
* Computed conditional probabilities

### 7. Probability Modeling

* Fitted Normal and Log-Normal distributions
* Compared empirical vs theoretical distributions
* Evaluated model fit visually and statistically

---

## 📊 Key Findings

* Housing prices are **positively skewed**, with a long right tail
* The **log-normal distribution** provides a better fit than the normal distribution
* Price variability is relatively high, indicating uncertainty
* Property features such as **view** significantly influence price distribution
* Conditional probability analysis reveals differences in likelihood across categories
* Empirical data deviates from ideal theoretical models, highlighting real-world complexity

---

## 🧠 Key Concepts Applied

* Probability distributions
* Skewness & kurtosis
* Expected value (E[X])
* Variance (Var(X))
* Probability density functions (PDF)
* Conditional probability (P(X | Y))
* Distribution fitting

---

## 🛠️ Technologies Used

* Python
* JupyterLab
* pandas
* numpy
* matplotlib
* seaborn
* scipy

---

## 🚀 How to Run

1. Clone the repository:

   ```bash
   git clone https://github.com/17s-sonnynguyen/real-estate-distribution-analysis.git
   ```

2. Navigate to the project directory:

   ```bash
   cd real-estate-distribution-analysis
   ```

3. Open JupyterLab:

   ```bash
   jupyter lab
   ```

4. Run the notebook step-by-step

---

## 📌 Conclusion

This project demonstrates how probability and statistical distributions can be applied to real-world data.
Understanding distribution behavior provides valuable insights into variability, uncertainty, and decision-making in real estate markets.

---

## 👤 Author

Sonny Nguyen