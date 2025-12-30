## 📊 Customer Churn Prediction (Random Forest + Feature Importance)
Predicting customer churn is vital for businesses to retain customers and reduce losses.  
This project uses a **Random Forest Classifier** to predict churn and analyze **feature importance** for key drivers.

---

## 🔎 Overview
- **Objective:** Identify customers likely to churn and the factors affecting churn.  
- **Dataset:** churn-bigml-80.csv (telecom dataset with 3993 rows, 21 columns)  
- **Workflow:**
  1. Data Preprocessing (encode categorical features)  
  2. Train/Test Split (80/20)  
  3. Model Training using **Random Forest**  
  4. Feature Importance Extraction  
  5. Visualization using **Seaborn Bar Plots**  
  6. Evaluation via Accuracy

---

## 📂 Project Structure
Customer-Churn-Prediction-(Random Forest)/  
- CCP.ipynb              # Jupyter Notebook (model + analysis)  
- churn-bigml-80.csv      # Dataset  
- requirements.txt        # Dependencies  
- README.md               # Documentation  

---

## ⚙️ Installation
Clone the repository and install dependencies:
```bash
git clone https://github.com/abdullahq-mlworks/CCP--Random-Forest-Feature-Importance-.git
cd CCP-(Random Forest+Feature Importance)
pip install -r requirements.txt
````

**Requirements:**
pandas
scikit-learn
seaborn
matplotlib
jupyter

---

## 🧾 Dataset

* **Features:** Numerical (Total day minutes, Total eve calls, Total intl charge, etc.), Categorical (State, International plan, Voice mail plan)
* **Target:** Churn (Yes/No)

---

## 🤖 Model

* **Algorithm:** RandomForestClassifier (sklearn.ensemble)
* **Hyperparameters:**

  * n_estimators = 100
  * max_depth = None
  * random_state = 42

---

## 📊 Results

* **Accuracy:** ~95%
* **Feature Importance:** Top features visualized using Seaborn bar plots, showing which attributes most influence churn predictions.

---

## 🚀 Future Work

* Compare with other models: XGBoost, Logistic Regression, SVM
* Hyperparameter Tuning (GridSearchCV / RandomizedSearchCV)
* Deploy as Streamlit or Flask Web App for interactive visualization

```

---

Agar chaho, main **even shorter version**, **2-3 paragraphs GitHub description style**, jo **repo main top me aa jaye**, bhi bana doon.  

Kya bna doon wo bhi?
```
