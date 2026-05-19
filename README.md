
# 🛒 Social Network Ads Purchase Prediction

A Machine Learning based web application that predicts whether a customer will purchase a product based on customer information such as Gender, Age, and Estimated Salary.

The project is developed using Logistic Regression with a FastAPI backend and an interactive Streamlit frontend.

---

# 📌 Features

- Predicts customer purchasing behavior
- Attractive Streamlit user interface
- FastAPI backend integration
- Logistic Regression Machine Learning model
- Real-time prediction results
- Simple and professional project structure

---

# 🚀 Technologies Used

- Python
- FastAPI
- Streamlit
- Pandas
- NumPy
- Scikit-learn
- Joblib
- Uvicorn

---

# 📂 Project Structure

```text
Social Network Ads
│
├── backend
│   ├── app.py
│   ├── train_model.py
│   ├── model.pkl
│   ├── scaler.pkl
│   ├── columns.pkl
│   └── Social_Network_Ads.csv
│
├── front_end
│   └── frontend.py
│
├── requirements.txt
└── README.md
````

---

# ⚙️ Machine Learning Workflow

1. Import Libraries
2. Load Dataset
3. Data Preprocessing
4. Convert Categorical Data
5. Split Dataset
6. Feature Scaling
7. Train Logistic Regression Model
8. Evaluate Model Performance
9. Save Model Files
10. Build FastAPI Backend
11. Build Streamlit Frontend

---

# 📊 Input Features

* Gender
* Age
* Estimated Salary

---

# 🎯 Output

* Customer Will Purchase
* Customer Will Not Purchase

---

# ▶️ Installation

## Step 1: Clone Repository

```bash
git clone https://github.com/sathwika9121/social-network-ads-purchase-prediction.git
```

---

## Step 2: Move to Project Folder

```bash
cd social-network-ads-purchase-prediction
```

---

## Step 3: Install Required Packages

```bash
pip install -r requirements.txt
```

---

# ▶️ Run Backend Server

Open terminal inside backend folder:

```bash
cd backend
python -m uvicorn app:app --reload
```

Backend runs at:

```text
http://127.0.0.1:8000
```

---

# ▶️ Run Streamlit Frontend

Open another terminal:

```bash
cd front_end
python -m streamlit run frontend.py
```

Frontend runs at:

```text
http://localhost:8501
```

---

# 📈 Model Used

* Logistic Regression

---

# 📷 User Interface

The project includes:

* Modern Gradient Background
* Interactive Input Components
* Real-time Predictions
* Attractive Streamlit UI

---

# 📌 Future Enhancements

* Deploy on Streamlit Cloud
* Add User Authentication
* Improve Model Accuracy
* Add More Customer Features
* Connect Database Support

---

# 👩‍💻 Author

### Sathwika Samudrala
