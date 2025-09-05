# Fraud Transaction Prediction  

This project is a **Fraud Detection System** built using **Python, Machine Learning, and Streamlit**.  
It predicts whether a financial transaction is **fraudulent** or **legitimate** based on transaction details.  

---

## 🚀 Features  
- Data preprocessing, feature engineering, and model training (`InternAssi.ipynb`)  
- Interactive **Streamlit web application** (`Fraud_Prediction.py`)  
- Simple UI to enter transaction details  
- Prediction Results:  
  - ✅ Safe Transaction  
  - ❌ Fraudulent Transaction  

---

## 🛠️ Tech Stack  
- Python  
- Pandas, NumPy, Scikit-learn  
- Joblib (model saving/loading)  
- Streamlit (web app)  

---

## 📂 Project Structure  
```
Fraud_Prediction/
│-- InternAssi.ipynb              # Jupyter Notebook (EDA, preprocessing, training)
│-- Fraud_Prediction.py           # Streamlit app for predictions
│-- fraud_detection_pipeline.pkl  # Trained ML pipeline (not uploaded)
│-- README.md                     # Documentation
│-- requirements.txt              # Python dependencies
```

---

## ⚙️ Installation & Setup  

### Clone the repository  
```bash
git clone https://github.com/<your-username>/<repo-name>.git
cd <repo-name>
```

### Create virtual environment (optional but recommended)  
```bash
python -m venv venv
venv\Scripts\activate         # Windows
source venv/bin/activate      # Mac/Linux
```

### Install dependencies  
```bash
pip install -r requirements.txt
```

### Run the Streamlit App  
```bash
streamlit run Fraud_Prediction.py
```

Then open browser at 👉 http://localhost:8501  

---

## 📊 Example Usage  
1. Select **Transaction Type** (PAYMENT, TRANSFER, CASH_OUT, DEPOSIT)  
2. Enter **Amount, Sender & Receiver Balances**  
3. Click **Predict**  
4. Model will classify as:  
   - ✅ Not Fraud  
   - ❌ Fraud  

---

## 👤 Author  
**Ajay Kumar**  
- 🎓 B.Tech Mechanical Engineering (NIT Durgapur)  
- 📍 Nainital, Uttarakhand  
- 💼 Aspiring Data Analyst & ML Enthusiast  

---

## 📜 License  
This project is licensed under the **MIT License** – free to use and modify.  
