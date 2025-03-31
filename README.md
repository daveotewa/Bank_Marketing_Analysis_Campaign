# 📊 Bank Marketing Campaign Analysis

This project analyzes a real-world bank marketing dataset to uncover key patterns in customer behavior and campaign performance. The goal is to identify what factors contribute most to successful term deposit subscriptions and to provide data-driven recommendations for improving future campaigns.

---

## 📁 Project Files

- `Bank_Marketing_Analysis_Final.ipynb` – Full notebook with data cleaning, visualizations, and predictive models  
- `bank_customers_train.csv` – Cleaned dataset used for analysis  

---

## 🎯 Objectives

- Analyze previous marketing campaign patterns  
- Visualize campaign outcomes by month, contact method, and customer demographics  
- Build predictive models (Logistic Regression & Random Forest)  
- Identify key drivers of successful marketing outcomes  

---

## 📌 Key Insights

1. **📅 Campaign Volume ≠ Success**  
   May had the highest number of client contacts but also the lowest conversion rate—highlighting that high volume doesn't guarantee better performance.

2. **📞 Previous Contact Improves Conversion**  
   Customers who were contacted in earlier campaigns (`previous > 0`) had a much higher likelihood of saying "yes" to the offer.

3. **📱 Contact Method Matters**  
   Telephone calls were more successful than cellular outreach, suggesting that communication channels influence customer response.

4. **🎓 Education & Profession Are Strong Predictors**  
   Customers with tertiary education and those working in administration, education, or retired showed better response rates.

5. **📉 Economic Conditions Influence Behavior**  
   External factors like `euribor3m` and `emp.var.rate` were correlated with customer responses—indicating that economic timing plays a role in success.

---

## 🔧 Tools & Technologies

- **Python** – Pandas, Seaborn, Matplotlib, Scikit-Learn  
- **Jupyter Notebook / Google Colab** – For development and visualization  
- **GitHub** – Version control and collaboration  

---

## 🤖 Modeling Summary

- Logistic Regression used to predict likelihood of subscription (binary classification)  
- Random Forest Classifier built for improved accuracy and feature importance  
- ROC curve and confusion matrix used to evaluate model performance  

---

## 📈 Visuals Included

- Campaign outcomes by month (bar plot)  
- Education level vs subscription status  
- Contact method vs conversion rate  
- Correlation heatmap  
- ROC curve & Feature Importance (Random Forest)  

---

## 🚀 How to Run This Project

1. Clone the repository:
   ```bash
   git clone https://github.com/daveotewa/bank-marketing-analysis.git
