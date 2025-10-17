# ⚽ Hypothesis Testing in Sports: FIFA World Cup Goal Analysis

## 📌 Project Overview

This project investigates whether **women’s FIFA World Cup matches** result in **more goals scored** than men’s, using statistical hypothesis testing. It demonstrates my ability to:

- Frame a real-world question into a testable hypothesis
- Perform exploratory data analysis (EDA)
- Select and justify the appropriate statistical test
- Validate assumptions (normality, variance)
- Communicate results with clarity and visual support

---

## 🎯 Research Question

> **Are more goals scored in women's international soccer matches than men's?**

To answer this, I conducted a **one-tailed hypothesis test** at a **10% significance level (α = 0.10)**.

- **Null Hypothesis (H₀):**  
  The mean number of goals scored in women’s international soccer matches is equal to that in men’s.

- **Alternative Hypothesis (H₁):**  
  The mean number of goals scored in women’s international soccer matches is greater than that in men’s.

---

## 🧪 Project Workflow

### 1. Exploratory Data Analysis (EDA)
- Loaded `men_results.csv` and `women_results.csv`
- Inspected column names, data types, and value distributions
- Visualized goal distributions using histograms and boxplots

### 2. Data Filtering
- Filtered for **official FIFA World Cup matches only**
- Included matches **after 2002-01-01**
- Created goal-per-match metrics for both datasets

### 3. Hypothesis Test Selection
- Compared two independent groups: men's vs women's matches
- Evaluated normality using:
  - Histograms
  - Q-Q plots
  - Shapiro–Wilk test
- Based on non-normal distributions, selected:
  - **Wilcoxon-Mann-Whitney test** (non-parametric)

### 4. Performing the Hypothesis Test
- Used both:
  - `pingouin.mwu()` with pivoted DataFrame
  - `scipy.stats.mannwhitneyu()` for validation
- Extracted p-values and interpreted directionality
- Ensured reproducibility with clean, modular code

### 5. Interpreting Results
- Compared p-value against α = 0.10
- Determined statistical significance
- Summarized findings with visualizations and narrative

---

## 📊 Tools & Libraries

- `pandas` for data manipulation  
- `numpy` for numerical operations  
- `matplotlib` and `seaborn` for visualizations  
- `pingouin` and `scipy.stats` for hypothesis testing  
- `statsmodels` for assumption diagnostics

---

## ✅ Key Skills Demonstrated

- Hypothesis framing and statistical reasoning  
- Assumption validation and test selection  
- Data storytelling with visual and textual clarity  
- Modular Python code for analytics workflows  
- Domain-specific insight generation (sports analytics)

---

## 📈 Results & Insights

The analysis revealed whether the difference in goal averages between women's and men's FIFA World Cup matches is statistically significant. Full results and interpretation are available in the notebook.

---

## 🚀 Why This Project Matters

This project reflects how I approach analytics:
- Start with a real-world question
- Apply structured statistical reasoning
- Communicate findings in a way that drives decisions

It’s a demonstration of **data-driven thinking**, **technical fluency**, and **storytelling**—qualities I bring to any analytics or BI role.

---

## 📬 Contact

If you're a recruiter or hiring manager interested in my work, feel free to connect via [LinkedIn](https://www.linkedin.com/in/arvind-kumar-560885231/) or reach out through GitHub.


