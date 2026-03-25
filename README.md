# Cervical Cancer Prediction using Machine Learning

## 📌 Project Overview

This project predicts the likelihood of cervical cancer using medical test data. It uses a **Support Vector Machine (SVM)** model to classify whether a patient has cervical cancer based on diagnostic features.

The goal is to demonstrate how machine learning can assist in early detection and decision-making in healthcare.

---

## 📂 Dataset

The dataset contains the following features:

* **PatientID** – Unique identifier for each patient
* **HPV_Test** – Result of HPV test
* **Colposcopy** – Colposcopy examination result
* **Biopsy** – Biopsy result
* **Cervical_Cancer** – Target variable (0 = No, 1 = Yes)

---

## ⚙️ Technologies Used

* Python 🐍
* Pandas (Data Handling)
* NumPy (Numerical Operations)
* Scikit-learn (Machine Learning)

---

## 🧠 Model Used

* **Support Vector Machine (SVM)**

  * Used for classification
  * Enabled probability prediction (`probability=True`)

---

## 🚀 How It Works

1. Load dataset from CSV file
2. Select input features:

   * HPV_Test
   * Colposcopy
   * Biopsy
3. Split data into training and testing sets
4. Train SVM model
5. Predict cervical cancer based on patient ID

---

## 📊 Example Output

```
Patient 3: Has cervical Cancer with a probability of 85.67%.
```

---

## ▶️ How to Run the Project

### 1. Clone the repository

```
git clone https://github.com/your-username/cervical-cancer-prediction.git
cd cervical-cancer-prediction
```

### 2. Install dependencies

```
pip install pandas numpy scikit-learn
```

### 3. Run the script

```
python cervical_cancer_program.py
```

---

## 🔍 Function Explanation

### `predict_cervical_cancer(patient_id)`

* Takes a **patient ID** as input
* Fetches corresponding data
* Predicts:

  * Cancer presence
  * Probability score

---

## 📈 Model Evaluation (Optional Improvement)

Currently, the project imports `accuracy_score` but does not use it. You can improve by adding:

* Accuracy calculation
* Confusion matrix
* Precision & recall

---

## ⚠️ Limitations

* Small dataset (not suitable for real-world medical decisions)
* Limited features (only 3 medical indicators)
* No data preprocessing or normalization

---

## 💡 Future Improvements

* Add more medical features
* Use larger real-world datasets
* Try advanced models:

  * Random Forest
  * XGBoost
  * Neural Networks
* Build a web app using:

  * Flask / FastAPI
  * React frontend

---

## 📜 License

This project is for educational purposes only.

---

## 🙌 Author

Sai Dhanesh.V

---
