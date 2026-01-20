# Personal Loan Campaign - Predictive Analysis

## 📌 Project Overview
The objective of this project is to help AllLife Bank identify potential customers who are most likely to convert from liability customers to personal loan customers. Using historical data on 5,000 customers, I built a classification model to optimize marketing efforts and increase the success rate of the bank's personal loan campaigns.

## 🛠️ Tech Stack & Skills
* **Language:** Python
* **Libraries:** Pandas, NumPy, Scikit-learn, Seaborn, Matplotlib
* **Algorithms:** Decision Tree Classifier (Unpruned & Pruned)
* **Key Techniques:** Hyperparameter Tuning (Pruning), Exploratory Data Analysis (EDA), Feature Importance, Model Evaluation (Accuracy, Recall, F1-Score).

## 🚀 Key Engineering & Analytical Highlights
* **Data-Driven Strategy:** Identified that **Income**, **Family size**, and **Education level** are the strongest predictors of loan acceptance.
* **Model Optimization:** Built an initial unpruned Decision Tree (potential overfitting) and then performed **Pruning** to improve generalization on unseen data.
* **Recall Priority:** Achieved a model that effectively identifies potential loan takers, ensuring the bank doesn't miss out on high-probability conversions.



## 📊 Results & Business Insights
* **Top Predictors:** Income and Average Credit Card Spending (CCAvg) are the most significant factors in predicting loan acceptance.
* **Conversion Opportunity:** Identified a large segment of active credit card users who do not yet have a personal loan as a primary cross-selling target.
* **Strategic Recommendations:** Recommended focusing marketing efforts on high-income undergraduate segments to maximize ROI on campaign spending.

## 💡 Key Learnings
* Understanding the trade-off between model complexity and generalization (Bias-Variance tradeoff).
* Visualizing decision boundaries and understanding how tree-based models make decisions.
EOF
