# 🚗 Predicting Uber Driver Activation 

## 📌 Overview  
This project analyzes a real-world business problem: understanding what factors influence whether someone who signs up for Uber actually goes on to complete their first trip as a driver. By leveraging predictive modeling and data visualization, we aim to help Uber refine its driver onboarding strategy and improve activation rates.

---

## 💡 Inspiration  
When brainstorming project ideas, we wanted something enjoyable and impactful. Our goal was to extract valuable insights from a relatively small dataset—showcasing how companies can still make smart decisions with limited data. We chose a StrataScratch dataset because it offered an authentic, real-world scenario where we could dig deep into a company's operational data and draw meaningful conclusions.

---

## 🔍 Problem Statement  
**How can Uber use limited signup data to predict whether a new driver will complete their first trip?**  
Our project dives into identifying the most significant predictors of driver activation, offering actionable recommendations to improve recruitment and onboarding processes.

---

## ⚙️ How It Works  
- **Dataset**: Contains driver signup data with features such as signup channel, device, referral source, and more.
- **Target Variable**: `started_driving` (binary classification: 1 if the driver completed their first trip, 0 otherwise)
- **Models Used**:
  - Random Forest Classifier
  - XGBoost (LightBoost)
- **Evaluation Metrics**:
  - Accuracy
  - Feature Importance
  - Confusion Matrix

---

## 🔨 Built With  
- 🐍 **Python** (pandas, scikit-learn, xgboost, matplotlib, seaborn)
- 📊 **Power BI** for dashboards and data storytelling
- 🤖 **Machine Learning** for classification and feature selection

---

## 📈 Key Features & Process  

### ✅ Predictive Modeling  

### 🔍 Exploratory Data Analysis (EDA)  

### 🧹 Data Preprocessing & Feature Engineering  

---

## 🚧 Challenges  
- Dealing with missing or inconsistent values.
- Balancing between adding engineered features and preventing overfitting.
- Translating model insights into actionable business recommendations.

---

## 🏆 Accomplishments  
- Created an end-to-end machine learning pipeline.
- Built an interactive Power BI dashboard to support business storytelling.
- Collaborated effectively as a team to deliver both technical depth and business value.

---

## 🎓 Learning Outcomes  
- Applied ML algorithms to a real business classification problem.
- Gained experience in building interpretable models and refining them through feature selection.
- Developed compelling visualizations in Power BI that drive decision-making.
- Learned how to turn raw data into a coherent and persuasive story for stakeholders.

---

## 🔮 What’s Next for the Unforeseen  
If external datasets become available, the next logical step is to compare our findings with a competitor like Lyft. This could uncover platform-specific behavioral insights and highlight where Uber might improve to gain a competitive edge in driver acquisition and retention.

---

## 📂 Folder Structure  
```
├── data/                    # Raw and cleaned datasets
├── notebooks/              # Jupyter Notebooks with EDA and modeling
├── visuals/                # Power BI exports and graphs
├── models/                 # Trained model files (if applicable)
└── README.md               # Project documentation (you are here)
```

---

## 🤝 Team  
**Project by:** Kento Morita, Phuong Duong, Vincent Perez, Ariel Liang
We’re a group of business analytics students passionate about solving real-world problems through data and machine learning.
