# 🍴 Cuisine Classification using Machine Learning  

## 📌 Project Overview  
This project focuses on building a **machine learning model** that classifies restaurants based on their cuisines. With the rapid growth of food delivery platforms, automatic cuisine classification helps improve **search recommendations, personalization, and customer experience**.  

## ⚙️ Methodology  
1. **Data Preprocessing**  
   - Dropped rows with missing cuisine values.  
   - Extracted the **primary cuisine** (first cuisine listed).  
   - Removed cuisines with very few samples to avoid noise.  
   - Handled missing numeric values using median imputation.  
   - Applied **One-Hot Encoding** to categorical variables.  
   - Label encoded the target cuisine variable.  

2. **Model Training**  
   - Used **Random Forest Classifier** with 100 estimators.  
   - Data split into **80% training** and **20% testing** using stratified sampling.  

3. **Model Evaluation**  
   - Calculated accuracy, precision, recall, and F1-score with `classification_report`.  
   - Analyzed misclassifications using a **confusion matrix**.  
   - Identified the most commonly confused cuisines.  

## 📊 Results  
- Accuracy is displayed after training.  
- A detailed classification report highlights performance per cuisine.  
- Misclassified cuisine pairs are shown in tabular format.  

## 🚀 Applications  
- Food delivery apps for personalized recommendations.  
- Restaurant management and analytics.  
- Market research for culinary insights.  

---

## 🖥️ How to Run  

1. Clone the repository:  
   ```bash
   git clone https://github.com/your-username/cuisine-classification.git
   cd cuisine-classification
