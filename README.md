# Customer-Review-Prediction-Model-eCommerce-Analytics

# 🛒 Customer Review Prediction Model – eCommerce Analytics

This project develops a predictive analytics system for **Nile**, a leading South American eCommerce platform, to identify customers most likely to leave positive product reviews. By leveraging advanced machine learning techniques, we aimed to boost the platform’s ROI and strengthen brand reputation by increasing the volume and quality of customer feedback.  

The project was built as part of the *Analytics in Practice* module at Warwick Business School.  

---

## 📂 Repository Contents

| File                             | Description                                                                                      |
|----------------------------------|--------------------------------------------------------------------------------------------------|
| `Group_number_15.py`             | Python script implementing data preprocessing, model training (XGBoost, GBDT, Random Forest).   |
| `Group_number_15_report.pdf`     | Detailed report outlining methodology, model evaluation, and business recommendations.           |
| `Group_number_15_ppt.pdf`        | Presentation summarizing the project objectives, outcomes, and stakeholder recommendations.     |
| `dataset.zip`                    | Compressed archive containing cleaned and feature-engineered datasets used for analysis.        |

---

## 📝 Project Overview

- **Objective**: Predict which customers are most likely to leave positive reviews (score 4 or 5) to support targeted engagement campaigns and increase ROI.  
- **Business Context**:  
  - 97% of consumers rely on online reviews for purchase decisions.  
  - Positive reviews directly influence sales and customer trust.  
- **Key Features**:  
  - Predictive targeting to maximize marketing efficiency.  
  - Integration into Nile’s email automation for follow-ups.  

---

## 🛠️ Tools & Techniques
- **Languages**: Python (pandas, scikit-learn, matplotlib)  
- **Algorithms**: XGBoost, Gradient Boosted Decision Trees (GBDT), Random Forest  
- **Frameworks**: CRISP-DM for analytics workflow design  
- **Visualization**: matplotlib, seaborn  

---

## 📊 Results & Insights

| Model               | Accuracy | Precision | Recall | F1-Score |
|---------------------|----------|-----------|--------|----------|
| XGBoost             | 81%      | 77%       | 61%    | 0.74     |
| GBDT                | 81%      | 78%       | 60%    | 0.73     |
| Random Forest       | 80%      | 72%       | 62%    | 0.68     |

- **XGBoost** achieved the most balanced performance with minimal overfitting.  
- **Key Predictors**: Delivery timing, payment value, and product categories significantly impacted review likelihood.  

---

## 📁 File Descriptions

### `Group_number_15.py`
- Implements data cleaning, feature engineering, and model training.  
- Includes evaluation metrics (confusion matrices, precision, recall, F1).  

### `Group_number_15_report.pdf`
- Explains the methodology:
  - Data preparation and merging (89,999 reviews).  
  - Feature engineering (delivery status, payment value).  
  - Model selection and comparative analysis.  
- Provides business recommendations based on insights.

### `Group_number_15_ppt.pdf`
- Executive summary presentation:
  - Business case for predicting review behavior.  
  - Key findings and stakeholder-oriented strategies.

### `dataset.zip`
- Cleaned dataset ready for ML pipeline:
  - Customer attributes, order details, delivery timelines, and review scores.

---

## 🚀 How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/<yourusername>/customer-review-prediction-model.git
   cd customer-review-prediction-model

