# Derivable Judgement — Statistical Analysis Project

## 📌 Project Overview

**Derivable Judgement** is a Python-based statistical analysis project built with a **synthetic dataset of 500 records**. The project demonstrates how statistical methods can be used to analyze relationships, differences, and uncertainty in data.

The notebook covers:

- Synthetic dataset generation
- Hypothesis formulation
- 95% confidence intervals
- Two-sample t-test
- Chi-square test of independence
- One-way ANOVA
- Covariance
- Pearson correlation

> 

---

## 🎯 Project Objectives

The main objectives of this project are to:

1. Generate a structured synthetic dataset.
2. Create derived variables such as `age_group`, `diabetes`, and `hypertension`.
3. Formulate statistical hypotheses.
4. Calculate confidence intervals for numerical variables.
5. Compare mean BMI between males and females.
6. Test the relationship between smoking status and diabetes.
7. Analyze BMI differences across age groups.
8. Measure the relationship between age and BMI using covariance and correlation.

---

## 🗂️ Dataset

The dataset contains **500 records** and includes the following variables:

| Column | Description |
|---|---|
| `record_id` | Unique record identifier |
| `age` | Age of the record |
| `weight` | Weight value |
| `gender` | Male / Female |
| `region` | North / South / East / West |
| `smoking_status` | Smoker / Non-Smoker / Former Smoker |
| `exercise_frequency` | Daily / Weekly / Rarely / Never |
| `bmi` | Body Mass Index value |
| `blood_pressure` | Blood pressure value |
| `cholesterol_level` | Cholesterol level |
| `glucose_level` | Glucose level |
| `age_group` | Derived age category |
| `diabetes` | Derived boolean variable based on glucose/BMI rules |
| `hypertension` | Derived boolean variable based on blood pressure/age rules |

---

## 🧪 Hypotheses

### Hypothesis 1 — Smoking Status vs Diabetes

**H₀:** Smoking status has no effect on diabetes prevalence.

**H₁:** Smoking status affects diabetes prevalence.

A **Chi-square test of independence** is used for this hypothesis.

### Hypothesis 2 — BMI vs Gender

**H₀:** Mean BMI is equal between males and females.

**H₁:** Mean BMI differs between males and females.

A **two-sample t-test** is used for this hypothesis.

---

## 📊 Statistical Methods

### 1. Confidence Interval

A 95% confidence interval is calculated for:

- Age
- Weight

The notebook uses the **t-distribution** to calculate the confidence interval for the sample mean.

### 2. Two-Sample T-Test

The project compares the BMI values of:

- Male records
- Female records

The significance level is **α = 0.05**.

### 3. Chi-Square Test

The project tests whether:

**Smoking Status ↔ Diabetes**

are statistically independent.

### 4. One-Way ANOVA

A one-way ANOVA is used to examine BMI across different age groups:

- 18–25
- 26–35
- 36–45
- 46–60
- 60+

### 5. Covariance and Pearson Correlation

The project measures the relationship between:

**Age ↔ BMI**

using:

- Covariance
- Pearson correlation coefficient
- Correlation p-value

---

## 📈 Results

The notebook produces the following results for the generated dataset:

| Analysis | Result |
|---|---:|
| Age 95% CI | 48.31 to 51.51 |
| Weight 95% CI | 69.09 to 71.79 |
| BMI vs Gender p-value | 0.7217 |
| Smoking Status vs Diabetes p-value | 0.8821 |
| Age Groups vs BMI ANOVA p-value | 0.6496 |
| Age vs BMI Pearson correlation | 0.0219 |
| Age vs BMI correlation p-value | 0.6258 |

At the **0.05 significance level**, the notebook's tests report **Fail to Reject H₀** for the t-test, Chi-square test, and ANOVA.

The Pearson correlation is close to zero, indicating that the generated dataset shows very little linear association between age and BMI.

---

## 🛠️ Technologies Used

- **Python**
- **NumPy**
- **Pandas**
- **SciPy**
- **Statsmodels**
- **Jupyter Notebook**

---





---

## ▶️ How to Run

Start Jupyter Notebook:

```bash
jupyter notebook
```

Open:

```text
Derivable Judgement .ipynb
```

Run the notebook cells from top to bottom.

---

## 🔄 Project Workflow

```text
Generate Synthetic Dataset
          ↓
Create Derived Variables
          ↓
Formulate Hypotheses
          ↓
Calculate Confidence Intervals
          ↓
Perform T-Test
          ↓
Perform Chi-Square Test
          ↓
Perform ANOVA
          ↓
Calculate Covariance & Correlation
          ↓
Interpret Statistical Results
```

---

## 💡 Key Learning Outcomes

This project demonstrates practical understanding of:

- Data generation with NumPy
- DataFrame creation with Pandas
- Feature/variable derivation
- Hypothesis testing
- Statistical significance
- Confidence intervals
- t-tests
- Chi-square testing
- ANOVA
- Covariance
- Pearson correlation
- p-value interpretation
- Basic statistical decision-making

---

## 📁 Project Structure

```text
Derivable-Judgement/
│
├── Derivable Judgement .ipynb
├── calcuation notbook.pdf
└── README.md
```

---


---

## 👤 Author

**Bhargav Prajapati**

BCA | Data Analysis Learner

---


