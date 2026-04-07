# EliteTech_Intern
📊 **EliteTech Internship Projects (End-to-End Data Science & ML Portfolio)**

A comprehensive collection of **4 hands-on projects** covering the complete pipeline of **Data Engineering → Machine Learning → Deployment → Optimization**.

---

## 🧠 **Task 1 – Data Pipeline Development (ETL)**

### 📌 Overview

Build a robust **data preprocessing pipeline** using the Titanic dataset.

### 🔑 Highlights

* 🧹 Data cleaning & missing value handling
* 🔤 Encoding categorical variables
* 📏 Feature scaling (numerical data)
* 💾 Saved pipeline for reuse (`joblib`)

### ▶️ Run

```bash
python etl.py --input titanic_raw.csv --out data/processed
```

### 📂 Outputs

* `processed.npy` → Clean dataset
* `preprocessor.joblib` → Reusable pipeline

---

## 🧠 **Task 2 – CIFAR-10 Image Classification (CNN)**

### 📌 Overview

Train a **Convolutional Neural Network (CNN)** to classify images into 10 categories.

### 🔑 Highlights

* 🧠 Deep Learning with TensorFlow/Keras
* 🖼️ CIFAR-10 dataset (60K images)
* 💾 Model saved as `.h5`
* 📊 High accuracy multi-class classification

### ▶️ Run

```bash
python train.py
```

### 📦 Output

* `cifar10_cnn_model.h5`

---

## 🚀 **Task 3 – End-to-End Deployment (API + Web App)**

### 📌 Overview

Deploy the trained model using:

* ⚡ **FastAPI** → Backend API
* 🌐 **Streamlit** → Frontend Web App

### 🔑 Highlights

* 🔌 REST API for predictions
* 🖼️ Upload image → get class prediction
* 🧩 Modular architecture (model + utils + API + UI)

### ▶️ Run API

```bash
uvicorn app:app --reload
```

### ▶️ Run Web App

```bash
streamlit run app.py
```

---

## 📈 **Task 4 – Optimization using Linear Programming (PuLP)**

### 📌 Overview

Solve a real-world **profit maximization problem** using Linear Programming.

### 🏭 Problem

Maximize:

```text
Profit = 40x + 30y
```

Subject to:

* Machine hours ≤ 100
* Materials ≤ 90

### 🔑 Highlights

* 📊 Decision variables & constraints
* ⚙️ Optimization using PuLP
* 📈 Feasible solution & maximum profit

---

## 🛠️ **Tech Stack**

* **Languages:** Python
* **ML/DL:** TensorFlow, Keras
* **Data Processing:** NumPy, Pandas, Scikit-learn
* **Deployment:** FastAPI, Streamlit
* **Optimization:** PuLP

---

## 📂 **Project Structure**

```bash
├── task1_etl/
├── task2_deep_learning/
├── task3_deployment/
├── task4_optimization/
```

---

## ⚡ **Key Takeaways**

* End-to-end **ML lifecycle implementation**
* Hands-on with **real datasets (Titanic, CIFAR-10)**
* Exposure to **deployment & optimization techniques**
* Strong foundation for **Data Science & AI roles**

---

## ⭐ **Why This Project Stands Out**

> Covers the **complete AI pipeline** — from raw data → trained model → deployed system → optimization problem solving.

---

If this portfolio helped or inspired you, consider giving it a ⭐ on GitHub!
