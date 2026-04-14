# 🏡 House Price Prediction

A Machine Learning project for predicting house prices using regression models such as **Random Forest** and **Decision Tree**. This project demonstrates the complete ML lifecycle, including data preprocessing, feature engineering, model training, hyperparameter tuning, and deployment using a Flask web application.

---

## 📌 Features

- **Data Preprocessing**
  - Handling missing values  
  - Data cleaning and transformation  

- **Feature Engineering**
  - Feature selection  
  - Creation of meaningful input variables  

- **Model Training**
  - Random Forest Regressor  
  - Decision Tree Regressor  

- **Model Optimization**
  - Hyperparameter tuning for improved accuracy  

- **Deployment**
  - Flask-based backend API  
  - Interactive HTML frontend  

---

## 🚀 Tech Stack

- **Programming Language**: Python 3  
- **Backend**: Flask  
- **Machine Learning**: Scikit-learn  
- **Data Processing**: Pandas, NumPy  
- **Frontend**: HTML, CSS  

---

## 📂 Project Structure

```bash
house-price-prediction/
│── app.py                        # Flask app for deployment
│── houseprice.ipynb             # Jupyter Notebook with ML workflow
│── index.html                   # Frontend HTML file
│── best_random_forest_model.pkl # Trained model
│── rf_tuned_model.pkl           # Tuned Random Forest model
│── model_features.pkl           # Feature set used for training
│── requirements.txt             # Project dependencies
│── README.md                    # Project documentation
│── LICENSE                      # MIT License
```

---

## ⚙️ Installation & Usage

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/YodhaAI/house-price-prediction.git
cd house-price-prediction
```

### 2️⃣ Install Dependencies
```bash
pip install -r requirements.txt
```

### 3️⃣ Run the Application
```bash
python app.py
```

### 4️⃣ Open in Browser
```
http://127.0.0.1:5000
```

---

## 📊 Dataset

- The model is trained on a housing dataset (e.g., **Ames Housing Dataset from Kaggle**)  
- You can replace it with your own dataset for customization and experimentation  

---

## 📸 Demo

👉 Add screenshot or GIF of your project UI here  

---

## 🔮 Future Improvements

- Deploy the application on:
  - Heroku  
  - Render  
  - Streamlit  

- Add advanced models:
  - XGBoost  
  - LightGBM  

- Improve UI:
  - Bootstrap  
  - React  

- Build a public API for external integrations  

---

## 📜 License

This project is licensed under the **MIT License**.  
You are free to use, modify, and distribute it.

---

## ⚡ Author

**Aryan Singh Rajput**  
Made with ❤️ and a passion for Machine Learning
