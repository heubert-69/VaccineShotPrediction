## 🧬 Vaccine Behavior Prediction System (H1N1 + Seasonal)

A real-world machine learning system built to predict **H1N1 and Seasonal influenza vaccination uptake** using behavioral, demographic, and health-related features. Developed on a DrivenData-style dataset with strong emphasis on feature engineering, ensemble learning, and model evaluation rigor.

---

## 🚀 Performance

* **Public Score (AUC): 0.8429**
* Strong generalization across two independent prediction tasks:

  * H1N1 Vaccine Uptake
  * Seasonal Vaccine Uptake

---

## 🧠 Key Ideas

* Behavioral causal feature chains (e.g., social exposure → protective behavior → health risk)
* Socioeconomic and occupational risk modeling
* Class imbalance handling (without harmful oversampling)
* Ensemble learning with both boosting and linear models

---

## 🏗️ Models Used

* Logistic Regression
* Ridge Classifier
* SGD Classifier
* AdaBoost
* Random Forest
* Gradient Boosting
* XGBoost
* LightGBM
* CatBoost
* Voting Ensembles (Soft Voting with optimized weights)

---

## ⚙️ Pipeline Highlights

* Robust preprocessing for mixed categorical + numerical data
* Stratified train/test splits
* Feature engineering with behavioral and causal structure
* Model comparison using:

  * F1 Score
  * Precision / Recall
  * ROC-AUC
  * Brier Score (calibration quality)
* Experiment tracking via **MLflow**

---

## 📊 Insights

* Seasonal vaccination is largely linear and stable across models
* H1N1 prediction is nonlinear and interaction-driven
* Ensemble diversity improves robustness but requires careful calibration
* SMOTE was found to degrade generalization for this dataset

---

## 📦 Tech Stack

* Python
* scikit-learn
* XGBoost / LightGBM / CatBoost
* MLflow
* pandas / numpy

---

## 📌 Takeaway

This project demonstrates how **behavioral feature engineering + ensemble learning + causal structure assumptions** can produce strong, real-world predictive performance in epidemiological modeling tasks.

---

