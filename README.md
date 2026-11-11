## <H1>Data Analytics with Python</H1>

<H3>A comprehensive guide and reference document covering the fundamental concepts, statistical methods, and machine learning techniques taught across ** Week 1 to Week 12 ** in the  ** Data Analytics with Python ** course .
</H3>
---

## Course Structure Overview

The course is designed to build a strong foundation in descriptive analytics, inferential statistics, predictive modeling, and unsupervised machine learning using Python.

```
Week 01-03: Fundamentals, Descriptive Statistics & Probability Distributions
Week 04-06: Hypothesis Testing, ANOVA & Simple Linear Regression
Week 07-09: Multiple Regression, Logistic Regression & Model Evaluation (ROC)
Week 10-12: Chi-Square Tests, Clustering Techniques & Decision Trees (CART)
```

---

## Weekly Curriculum Breakdown

### **Week 1: Introduction to Data Analytics & Python Fundamentals**
* **Data Analytics Overview:** Types of analytics (Descriptive, Diagnostic, Predictive, Prescriptive), life cycle of analytics projects.
* **Python Basics:** Data types, variables, lists, tuples, dictionaries, sets, loops, conditional statements, and functions.
* **Essential Libraries:** Introduction to NumPy (arrays, vectorization) and Pandas (Series, DataFrames).
* **Descriptive Statistics:**
  * Measures of Central Tendency (Mean, Median, Mode).
  * Measures of Dispersion (Range, Interquartile Range, Variance, Standard Deviation).

---

### **Week 2: Probability Theory & Distributions**
* **Foundations of Probability:** Basic terminology, independent events, mutually exclusive events, conditional probability, and Bayes' Theorem.
* **Random Variables:** Discrete vs. continuous random variables.
* **Probability Distributions:**
  * **Discrete:** Binomial, Poisson distribution.
  * **Continuous:** Uniform, Normal distribution, and Standard Normal Distribution ($Z$-score).
* **Properties of Normal Curve:** Empirical rule, skewness, and kurtosis.

---

### **Week 3: Sampling, Sampling Distributions & Confidence Intervals**
* **Sampling Methods:** Random vs. non-random sampling, sampling error.
* **Sampling Distributions:** Central Limit Theorem (CLT) and distribution of sample means.
* **Distribution of Variance:** Sample variance properties and Chi-Square distribution concept.
* **Point Estimation & Interval Estimation:**
  * Confidence Intervals for single population mean (when population variance is known vs. unknown using $t$-distribution).
  * Confidence Intervals for population proportions.
* **Python Implementation:** Simulating distributions and plotting confidence intervals.

---

### **Week 4: Hypothesis Testing (One-Sample Tests)**
* **Hypothesis Formulation:** Null hypothesis ($H_0$) vs. Alternative hypothesis ($H_1$).
* **Decision Errors:** Type I Error ($\alpha$), Type II Error ($\beta$), and Statistical Power ($1 - \beta$).
* **Decision Rules:** Rejection regions, Critical values, and $p$-value approach.
* **One-Sample Tests:**
  * $Z$-test for single mean.
  * One-sample $t$-test.
  * Hypothesis tests for single population proportion.

---

### **Week 5: Two-Sample Testing & Introduction to ANOVA**
* **Two-Sample Hypothesis Tests:**
  * Independent two-sample $t$-test (equal vs. unequal variances).
  * Paired sample $t$-test (dependent samples).
  * Two-sample proportion tests.
* **Analysis of Variance (ANOVA):**
  * One-Way ANOVA: Concept, assumptions, and partitioning sum of squares (Between vs. Within groups).
  * $F$-test and calculation of the $F$-statistic.
* **Post-Hoc Analysis:** Pairwise comparisons using Tukey's HSD test.

---

### **Week 6: Two-Way ANOVA & Simple Linear Regression**
* **Experimental Design:** Randomized Block Design (RBD).
* **Two-Way ANOVA:** Main effects and interaction effects between two categorical factors.
* **Introduction to Simple Linear Regression:**
  * Concept of dependent ($Y$) vs. independent ($X$) variables.
  * Ordinary Least Squares (OLS) method for fitting the line.
  * Interpretation of regression coefficients (intercept and slope).
  * Goodness of fit: Coefficient of determination ($R^2$).

---

### **Week 7: Multiple Linear Regression & Residual Diagnostics**
* **Multiple Linear Regression (MLR):** Modeling relationships with multiple predictors.
* **Categorical Predictors:** Creating and interpreting dummy variables.
* **Model Assumptions & Residual Analysis:**
  * Linearity, independence, homoscedasticity, normality of residuals.
  * Detecting violations through residual plots and diagnostic metrics.
* **Multicollinearity:** Variance Inflation Factor (VIF) and remedies.
* **Feature Selection:** Adjusted $R^2$, step-wise regression concepts.

---

### **Week 8: Maximum Likelihood Estimation & Logistic Regression**
* **Maximum Likelihood Estimation (MLE):** Principles, likelihood function, and log-likelihood.
* **Transition to Classification:** Why linear regression fails for binary categorical outcomes.
* **Logistic Regression:**
  * Odds, Log-odds (Logit transformation), and Sigmoid function.
  * Parameter estimation via Maximum Likelihood.
  * Interpreting odds ratios and logistic regression coefficients.

---

### **Week 9: Model Building, Evaluation & ROC Curves**
* **Classification Evaluation Metrics:**
  * Confusion Matrix (True Positive, False Positive, True Negative, False Negative).
  * Accuracy, Precision, Recall (Sensitivity), Specificity, and $F_1$-Score.
* **ROC & AUC:**
  * Receiver Operating Characteristic (ROC) curve analysis.
  * Area Under the Curve (AUC) as an evaluation threshold.
* **Advanced Model Building:** Interaction terms, polynomial regression, and model validation techniques.

---

### **Week 10: Chi-Square Tests & Introduction to Cluster Analysis**
* **$\chi^2$ (Chi-Square) Tests:**
  * Test of Independence for contingency tables.
  * Goodness-of-Fit test for categorical distributions.
* **Unsupervised Learning Fundamentals:** Difference between supervised and unsupervised learning.
* **Introduction to Clustering:** Distance and similarity measures (Euclidean, Manhattan distance).
* **Data Preparation for Clustering:** Standardization and scaling ($z$-score scaling, Min-Max).

---

### **Week 11: Cluster Analysis (Partitional & Hierarchical)**
* **$K$-Means Clustering:**
  * Algorithmic steps and centroid updates.
  * Determining optimal clusters: Elbow Method (Inertia/WCSS) and Silhouette Score.
* **Hierarchical Clustering:**
  * Agglomerative vs. Divisive approaches.
  * Linkage criteria: Single, Complete, Average, and Ward's method.
  * Dendrogram interpretation and cutting trees to form clusters.

---

### **Week 12: Decision Trees (CART)**
* **Classification and Regression Trees (CART):** Structure, root node, internal nodes, and leaf nodes.
* **Attribute Selection Measures:**
  * Entropy and Information Gain.
  * Gini Impurity (used in CART).
  * Mean Squared Error (MSE) reduction for continuous regression trees.
* **Tree Optimization:** Overfitting prevention, stopping criteria, and pruning techniques.

---

## Core Tooling & Libraries

| Library | Primary Use Case |
|---|---|
| **Python** | Core language for implementation |
| **NumPy** | Numerical operations and array manipulation |
| **Pandas** | Tabular data loading, wrangling, and exploration |
| **Matplotlib / Seaborn** | Data visualization and diagnostic plotting |
| **SciPy / Statsmodels** | Statistical testing, ANOVA, and regression tables |
| **Scikit-Learn** | Machine learning (Logistic Regression, $K$-Means, CART) |

---

## Learning Path Summary

```
1. Descriptive Statistics & Python Setup
              │
              ▼
2. Probability & Sampling Foundations
              │
              ▼
3. Parametric & Non-Parametric Hypothesis Tests
              │
              ▼
4. Supervised Linear & Logistic Predictive Modeling
              │
              ▼
5. Unsupervised Clustering & Decision Tree Classifiers
```