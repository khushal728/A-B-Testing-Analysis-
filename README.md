# A-B-Testing-Analysis-(Digital Marketib)

## 📌 Project Overview

This project focuses on performing A/B testing to evaluate whether a new webpage design (treatment group) results in a higher conversion rate compared to the existing design (control group). The goal is to apply statistical testing to determine the effectiveness of the marketing strategy.

## 🧪 Objective

To determine if there is a statistically significant difference in conversion rates between the control and treatment groups.

## 📁 Dataset Description

Total Entries: 294,478

Columns:

user_id

group (control or treatment)

landing_page (old_page or new_page)

converted (0 or 1)

## 🧹 Data Cleaning

Detected and removed 3894 mismatches between group and landing page combinations.

Final cleaned dataset: 290,585 rows

## 📊 Conversion Rate Results

Control Group (A): 12.04%

Treatment Group (B): 11.88%

## 🧠 Statistical Testing

Method: Two-sample z-test

Null Hypothesis (H0): Conversion rates of both groups are the same

Alternative Hypothesis (H1): Conversion rates are different

P-value: 0.19

Conclusion: Failed to reject the null hypothesis. No significant difference in conversion rates

## 📈 Tools Used

Python

Pandas

Matplotlib / Seaborn

Scipy (statsmodels for z-test)

## 📚 Learnings

Cleaning data inconsistencies is critical before hypothesis testing

Small differences need to be backed by statistical evidence

A/B testing is a powerful tool for decision-making in product and marketing teams

## 📬 Contact

For questions, reach out via:

GitHub: khushal728

LinkedIn:(https://www.linkedin.com/in/khushal-joshi-64161a2b7/)




























