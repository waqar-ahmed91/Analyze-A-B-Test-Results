# 📊 A/B Test Results Analysis

This project demonstrates a comprehensive analysis of A/B testing, leveraging statistical methods to help an e-commerce company make informed decisions about launching a new web page. The project covers key areas of statistics including probability, hypothesis testing, and regression modeling.

---

## 🧾 Table of Contents

1. [Introduction](#introduction)  
2. [Part I - Probability](#part-i---probability)  
3. [Part II - A/B Test](#part-ii---ab-test)  
4. [Part III - Regression](#part-iii---regression)  
5. [Conclusions](#conclusions)  
6. [Tools Used](#tools-used)  
7. [Author](#author)

---

## 📘 Introduction

A/B testing is a critical tool in data-driven decision making, especially in digital product development and marketing. In this project, we analyze the results of an A/B test run by an e-commerce platform to determine whether they should:

- Launch the **new page**,
- Retain the **existing page**, or
- **Extend the experiment** to collect more evidence.

This project assesses your ability to apply statistics, perform hypothesis testing, and evaluate the results of an experiment under realistic conditions.

---

## 🎲 Part I - Probability

In this section, we:
- Explore and summarize the dataset
- Validate assumptions such as equal sample sizes
- Calculate observed probabilities for conversions in both control and treatment groups
- Evaluate randomness and assignment of users to groups

---

## 📈 Part II - A/B Test

This section involves:
- Formulating **null and alternative hypotheses** to test if the new page performs better than the old page
- Simulating sampling distributions under the null hypothesis
- Computing **p-values** and comparing them to significance levels (α = 0.05)
- Drawing statistical conclusions based on test statistics and confidence intervals

> **Hypotheses:**
> - **Null (H₀)**: The new page has the same or lower conversion rate than the old page  
> - **Alternative (H₁)**: The new page has a higher conversion rate than the old page

---

## 📊 Part III - Regression

We further:
- Apply **logistic regression** to model conversion as a function of landing page and other covariates
- Interpret regression coefficients
- Evaluate the statistical significance of model parameters
- Analyze whether other factors (e.g., user location or timestamp) influence conversions

---

## ✅ Conclusions

- Based on statistical evidence, there was **no significant improvement** in conversion rates for users on the new page.
- **Regression analysis** also did not show a strong correlation between page version and conversion.
- Recommendation: **Do not roll out the new page yet.** Consider further testing or exploring potential confounding variables.

---

## 🛠️ Tools Used

- Python
- Pandas & NumPy
- SciPy & Statsmodels
- Matplotlib & Seaborn
- Jupyter Notebook

---

## 👤 Author

**Waqar Ahmed**  
📧 Email: waqar.nu@gmail.com  
🔗 GitHub: [waqar-ahmed91](https://github.com/waqar-ahmed91)

---

> **Disclaimer:** This project is for educational purposes and was built as part of a data science learning program.
