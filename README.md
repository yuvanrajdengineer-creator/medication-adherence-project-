# 🩺 Medication Adherence Prediction using Machine Learning  
A Pharm.D + Data Science Project

Medication non-adherence leads to treatment failure, hospitalizations, and increased healthcare costs.  
This project uses *Machine Learning (ML)* to predict which patients are at high risk of not following their medications, so pharmacists can intervene early.

---

## 📌 Project Goals
This project was created to:

- Generate a realistic synthetic dataset for medication adherence  
- Perform exploratory data analysis (EDA)  
- Train and evaluate two ML models  
  - Logistic Regression  
  - Random Forest  
- Identify key predictors of non-adherence  
- Save trained models for deployment (Streamlit / Flask)

---

## 📂 Project Structure

medication-adherence-project/
│
├── data/
│   └── med_adherence_dataset.csv
│
├── models/
│   ├── logistic_model.pkl
│   └── small_random_forest_model.pkl
│
├── notebook/
│   └── medication_adherence_project.ipynb
│
└── README.md


---

## 📊 Key Findings
- Higher *side effects* → lower adherence  
- More *number of medicines per day* → lower adherence  
- *Counselling* significantly improves adherence  
- *Forgetfulness score* strongly predicts non-adherence  
- Chronic diseases (ex: *Asthma*) show higher dropout risk  

These insights match real-world pharmacy practice.

---

## 🧠 Machine Learning Models
### *⿡ Logistic Regression*
- Interpretable  
- Good baseline model  

### *⿢ Random Forest (Optimized Small Version)*
- Higher performance  
- Reduced model size (<25 MB for GitHub)  
- Good at capturing interactions  

---

## 📈 Model Evaluation Metrics
- Accuracy  
- Precision  
- Recall  
- F1 Score  
- ROC-AUC  

---

## 🚀 How to Run the Project

### *1. Clone the repository*
bash
git clone https://github.com/<your-username>/medication-adherence-project.git
cd medication-adherence-project


### *2. Install requirements*
bash
pip install -r requirements.txt


### *3. Open the notebook*
bash
jupyter notebook


---

## 🛠 Tech Stack
- Python  
- Pandas, NumPy  
- Scikit-learn  
- Matplotlib, Seaborn  
- Google Colab  
- Joblib  

---

## 💡 Future Improvements
- Build a Streamlit Web App for real-time prediction  
- Add SHAP explainability charts  
- Improve model performance  
- Create mobile-friendly UI for pharmacists  

---

## 👨‍⚕ About Me
*Yuvan Raj B*  
Pharm.D Student | Beginner in Data Science  
Interested in healthcare analytics, ML in medicine, and clinical decision support.

---

## ⭐ Acknowledgment
This project was created for learning purposes to combine *pharmacy knowledge* with *machine learning* to improve patient outcomes.
