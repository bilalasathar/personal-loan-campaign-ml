# 💸 Personal Loan Campaign – Classification Project

A machine learning project aimed at predicting the likelihood of personal loan adoption among AllLife Bank's liability customers. Using a Decision Tree classifier, this project helps uncover the customer attributes that most influence loan acceptance to support more effective and targeted marketing strategies.

---

## 🎯 Objective

To build a binary classification model that predicts whether a customer will accept a personal loan offer, using customer profile and banking-related features. The goal is to help the bank improve the effectiveness of future marketing campaigns.

---

## 🧰 Tools & Technologies

- **Language**: Python
- **Libraries**: Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn
- **Model**: Decision Tree Classifier
- **Notebook Format**: Jupyter Notebook (HTML export provided)

---

## 🔍 Key Steps

1. **Data Understanding**  
   Explored customer attributes including income, age, experience, account balances, and product usage.

2. **EDA (Exploratory Data Analysis)**  
   - Visualized relationships between variables and the loan acceptance rate.
   - Checked for outliers, distributions, and categorical variable balance.

3. **Data Preprocessing**  
   - Handled irrelevant columns.
   - Converted categorical variables.
   - Normalized numerical fields where needed.

4. **Model Building**  
   - Trained a Decision Tree classifier.
   - Evaluated model using accuracy, precision, and recall.
   - Analyzed **feature importance** to identify which variables influenced the outcome most.

5. **Model Evaluation**  
   - Compared predictions with actual labels.
   - Discussed marketing implications for high-probability customer groups.

---

## 📊 Key Insights

- Feature Importance:Across all Decision Tree models (default, pre-pruned, post-pruned), Education and Income were the most influential features in predicting personal loan acceptance. These attributes are critical for customer profiling.
- Model Performance:The post-pruned Decision Tree performed best, offering improved F1 score, precision, and recall. Its ability to generalize better on unseen data makes it ideal for deployment in real-world scenarios.
**Business Recommendations:**
  - AllLife Bank should prioritize collecting accurate income and education data to enhance loan targeting.
  - Targeted marketing campaigns can be crafted for customer groups with higher loan adoption likelihood based on these attributes.
  - The post-pruned model can be integrated into the loan approval or marketing decision pipeline for better conversion and outreach efficiency.
---


