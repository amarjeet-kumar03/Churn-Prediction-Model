# 🧠 Customer Churn Prediction App

An interactive web application that predicts whether a customer will churn (leave a business) using a trained Machine Learning model.  
Built using **Streamlit**, it accepts customer inputs and provides churn predictions in real time.

---

## 💡 About The Project

Customer churn prediction is a critical business problem — it helps companies identify customers who are likely to leave and enables proactive retention strategies.

This application:
- Loads a trained Artificial Neural Network (ANN) churn model
- Preprocesses input data using saved encoders and scaler
- Predicts churn outcome based on user input

---

## 🚀 Features

✔ User-friendly Streamlit interface  
✔ Real-time prediction for new customer inputs  
✔ Preprocessing using saved encoders and scaler  
✔ ANN model for binary classification  
✔ Easy to extend for new features

---

## 📦 Folder Structure

├── ann_churn_model.h5
├── app.py
├── Churn_Modelling.csv
├── label_encoder_gender.pkl
├── onehot_encoder_geo.pkl
├── prediction.py
├── requirements.txt
├── scaler.pkl
├── train_ann_model.py


---

## 🛠️ Built With

This project uses the following major Python libraries:

- [Python](https://www.python.org/)
- [Streamlit](https://streamlit.io/)
- [TensorFlow / Keras](https://www.tensorflow.org/)
- [NumPy](https://numpy.org/)
- [Pandas](https://pandas.pydata.org/)
- [Scikit-Learn](https://scikit-learn.org/)

---

## 🧠 How It Works

### 1. Data Preprocessing
- Categorical features are encoded using label and one-hot encoding
- Numerical features are scaled

### 2. Model Training
- An ANN model is trained on customer data
- Model is saved to disk for reuse

### 3. Prediction
- Streamlit app loads model + encoders
- Inputs from user UI
- Outputs churn result

---

## 🧪 Getting Started

### 🔹 Prerequisites

Make sure you have Python 3.x installed.

### 🔹 Install Dependencies

```bash
pip install -r requirements.txt
🔹 Run The Application
streamlit run app.py
🖼️ Demo Screenshots
(Optional — Add screenshots of your Streamlit app here)

🧾 Usage
Enter customer details (e.g., geography, credit score, age, balance, etc.)

Click Predict

Output will show whether the customer is likely to churn or stay

📈 Results
This model outputs:

A probability score

A binary prediction (Churn vs No Churn)

Results can be used for business planning and customer retention strategies.

🎯 Who Is This For?
✔ Students learning ML classification
✔ Developers building prediction apps
✔ Business analysts studying churn risk models

📜 License
This project is for educational purposes.

🙌 Acknowledgements
Thanks to open-source libraries and community support.


---

### Want Extra Enhancements?

I can also generate:

✅ A **project poster / one-pager summary**  
✅ A **resume project description** (2–3 lines)  
✅ A **Viva prep sheet**  
✅ A **requirements.txt** (if not already complete)

Just tell me what you need next! 🚀
::contentReference[oaicite:0]{index=0}
