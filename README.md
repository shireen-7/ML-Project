🎓 Fraud Risk Prediction System

📌 Project Overview

This project focuses on detecting fraudulent financial transactions using Machine Learning techniques. The system analyzes transaction data and predicts whether a transaction is fraudulent (1) or legitimate (0).

The goal is to build a highly accurate and reliable fraud detection model, with special focus on identifying rare fraud cases.

🎯 Problem Statement

Financial fraud is a major issue in digital transactions. Since fraud cases are very rare compared to normal transactions, traditional models fail to detect them effectively.

This project aims to:

Handle imbalanced data
Improve fraud detection rate (recall)
Build robust predictive models

📂 Dataset Used

Dataset: Financial Transactions Dataset (Kaggle)
Contains details like:
Transaction type
Amount
Account balances before and after transaction
Fraud label (isFraud)

⚙️ Technologies Used

Python 🐍
Pandas & NumPy
Matplotlib & Seaborn (Visualization)
Scikit-learn
Imbalanced-learn (SMOTE)

🤖 Models Used

1. Logistic Regression
Simple and fast baseline model
Works well with scaled data

3. Random Forest 🌳
Handles non-linear patterns
High accuracy and stability

5. Gradient Boosting 🚀
Sequential learning
Strong performance on complex data

📊 Model Performance

Model	Accuracy

Logistic Regression	97.6%

Random Forest	99.97%

Gradient Boosting	99.97%

👉 Random Forest achieved the best balance between accuracy and recall.

📌 Key Insights

Dataset was highly imbalanced → handled using SMOTE
Recall is more important than accuracy in fraud detection
Ensemble methods improve robustness
Feature engineering significantly improved performance
🚀 Outcome

The project successfully built a high-performance fraud detection system capable of identifying fraudulent transactions with high accuracy and good recall.

📁 Project Structure

Fraud-Detection/
│
├── data/
├── notebook.ipynb
├── README.md
└── requirements.txt

🔗 Future Improvements

Use deep learning models
Deploy as a web application
Real-time fraud detection system

👩‍💻 Author

INARA SHIREEN

⭐ Conclusion

This project demonstrates how Machine Learning can be effectively used to detect fraud in financial systems, with proper handling of imbalanced data and model optimization.
