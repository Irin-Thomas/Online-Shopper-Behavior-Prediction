# 🛒 Online Shopper Behavior Prediction – Machine Learning Project

This project explores online shopper behavior using **supervised** and **unsupervised machine learning techniques** on the [UCI Online Shoppers Purchasing Intention Dataset](https://archive.ics.uci.edu/ml/datasets/Online+Shoppers+Purchasing+Intention+Dataset). The primary goal is to predict purchase intentions and segment customer behavior to derive actionable insights for **e-commerce optimization**.

---

## 📊 Project Overview

- **Dataset Used:** Online Shoppers Purchasing Intention Dataset (UCI)
- **Techniques Applied:**
  - Supervised Learning: **Decision Tree**, **Random Forest**
  - Unsupervised Learning: **K-Means Clustering**
- **Key Features:** `PageValues`, `ExitRates`, `ProductRelated_Duration`
- **Evaluation Metrics:** Accuracy, F1-Score, Silhouette Score

---

## 🔍 Objectives

- Predict whether a user will make a purchase based on clickstream and session data.
- Identify **customer segments** using clustering to understand engagement levels.
- Determine **key behavioral predictors** of conversion.
- Provide **data-driven recommendations** to improve user experience and conversion rates.

---

## 🧠 Machine Learning Models

### ✅ Supervised Learning

| Model           | Accuracy | F1-Score |
|----------------|----------|----------|
| Decision Tree  | 0.87     | 0.61     |
| Random Forest  | 0.89     | 0.66     |

- **Random Forest** performed best, confirming the hypothesis that ensemble methods are more effective for complex classification tasks.
- `PageValues` was identified as the **most important feature**, highlighting the importance of showing high-value content.
- `ExitRates` and `ProductRelated_Duration` were also influential predictors.

###  🔄 Unsupervised Learning

**K-Means Clustering** identified two major user groups:
- **Cluster 1:** Casual browsers with low engagement.
- **Cluster 2:** Highly engaged users with high exit rates, suggesting friction in the purchase journey.

---

## 📈 Key Insights

- Meaningful interaction with product pages increases conversion likelihood.
- Users with high `ExitRates` but high initial engagement may abandon due to UX issues.
- Clustering helps target marketing strategies more effectively.

---

## 💡 Recommendations

- Improve the design and functionality of high-exit pages to support Cluster 2 users.
- Apply more advanced ensemble models like **Gradient Boosting** or **XGBoost**.
- Engineer features that capture **temporal** behavior or session sequencing.
- Explore deeper clustering using **DBSCAN** or **hierarchical clustering** for nuanced segments.

---

## 📚 References
- Citations and source materials are listed in the final report PDF [Online Shoppers Purchasing Intention-Irin Mary Thomas.pdf](https://github.com/Irin-Thomas/Online-Shopper-Behavior-Prediction/blob/main/Report/Online%20Shoppers%20Purchasing%20Intention-Irin%20Mary%20Thomas.pdf)
- [UCI Machine Learning Repository - Online Shoppers Purchasing Intention Dataset](https://archive.ics.uci.edu/dataset/468/online+shoppers+purchasing+intention+dataset)

## 📬 Contact
Author: Irin Mary Thomas
Email: irinthomas0@gmail.com


