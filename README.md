# Hypothesis_Testing_Startup_Survival
Startup Survival Analysis using Hypothesis Testing

DOMAIN: Startup Ecosystem

## OBJECTIVE:
The objective of this project is to conduct **Hypothesis Testing** to understand the **financial factors** that differentiate thriving, **currently operating startups from those that ultimately cease operations**.

In particular, to address the critical questions of **whether there is a statistically significant difference in the mean funds raised by startups** that are currently operating compared to those that have ceased operations. Additionally, we aim to investigate **whether there exists a significant disparity in the number of funding rounds** between currently operating startups and startups that have closed.

## DATA:
The dataset comprises of the information about startups in India.

📌 **DATASET** *: https://www.kaggle.com/datasets/yanmaksi/big-startup-secsees-fail-dataset-from-crunchbase* *(Filter on country and status column)*

## **HYPOTHESIS TESTING I:**

**Mean Funds Raised**

💡 **Null Hypothesis (H0):** There is no statistically significant difference in the mean funds raised by currently operating startups and startups that have closed.

💡 **Alternative Hypothesis (H1):** There is a statistically significant difference in the mean funds raised by currently operating startups and startups that have closed.

## **HYPOTHESIS TESTING II:**

**Number of Funding Rounds**

💡 **Null Hypothesis (H0):** There is no statistically significant difference in the number of funding rounds between currently operating startups and startups that have closed.

💡 **Alternative Hypothesis (H1):** There is a statistically significant difference in the number of funding rounds between currently operating startups and startups that have closed.

## KEY LEARNINGS:

### Reasons for choosing the below-mentioned statistical tests 📢

⏬ **INDEPENDENT T-TEST UNKNOWN VARIANCE ASSUMED TO BE EQUAL**

- Two separate and independent groups which **are distinct and unrelated in terms of their current status.**
- T-test is designed for **comparing means of continuous numerical data.**
- The t-test assumes that the **data within each group follows a normal distribution.**
- **Homogeneity of Variance:** We must check that using **Levene’s Test.**

⏬ **LEVENE’S TEST**

- The Levene's Test is a statistical test used to **assess whether the variances of two or more groups are equal or homogenous.**

⏬ [**CHI-SQUARE TEST OF INDEPENDENCE**](https://www.notion.so/Hypothesis-Testing-4be9c8d45e2347a3a9e2e29a6ca1d734?pvs=21)

- This used whenever we need to find if there is any **statistically significant association or relationship** between two categorical variables.
- The observations are independent and cells in the **contingency table are mutually exclusive.**
- We need to check if the **expected value of cells should be 5 or greater in at least 80% of cells.**

## ****CONCLUSION****

### **HYPOTHESIS TESTING I (MEAN FUNDS RAISED) :**
📌Independent Sample T-Test for Equal Variances.
 
**RESULT:**

The **p-value, which is greater than the chosen alpha level (i.e., 0.54 > 0.05),** leads us to **fail to reject the null hypothesis with 95% confidence.**

There is **no statistically significant difference in the funds raised by currently operating startups and startups that have closed,** as per the independent sample t-test.

### **HYPOTHESIS TESTING II (NUMBER OF FUNDING ROUNDS) :**
📌 Chi-Square Test of Independence.

**RESULT:**

The **p-value, which is greater than the chosen alpha level (i.e., 0.29 > 0.05),** leads us to **fail to reject the null hypothesis with 95% confidence.**

There is **no statistically significant association between the number of funding rounds and the status of startups,** as indicated by the Chi-Square Test of Independence.

## THANK YOU!! :)

View my project in Notion : https://windy-geese-6b2.notion.site/Hypothesis-Testing-4be9c8d45e2347a3a9e2e29a6ca1d734?pvs=4
