# 🎯 Placement Predictor (Machine Learning Project)

## 📌 Overview

This project predicts whether a student will get placed or not based on:

* CGPA
* IQ

It uses **Logistic Regression** model.

---

## 📂 Project Structure

```
placement-predictor/
 ├── model.pkl        # Trained ML model
 ├── placement.csv    # Dataset
```

---

## ⚙️ How to Use

### 1. Load the model

```python
import pickle

model = pickle.load(open('model.pkl', 'rb'))
```

---

### 2. Make prediction

```python
model.predict([[7.0, 120]])
```

👉 Output:

* `1` → Placed
* `0` → Not Placed

---

## 🧠 Tech Used

* Python
* Scikit-learn
* Pandas
* NumPy

---

## 🚀 Future Improvements

* Add web app (Flask/FastAPI)
* Add UI for user input
* Deploy online

---

## 👨‍💻 Author

**Machine_ritesh**

