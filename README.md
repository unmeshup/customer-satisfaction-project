# 📊 Customer Satisfaction Prediction (Machine Learning Project)

## 🧠 Overview
This project aims to predict **customer satisfaction ratings (1–5)** using machine learning techniques on customer support ticket data. The model analyzes factors such as ticket type, priority, response time, and customer demographics to understand and predict satisfaction levels.

---

## 🎯 Objective
To build a machine learning model that can accurately predict **customer satisfaction rating** based on customer service interactions and ticket-related features.

---

## 📁 Dataset Information
The dataset contains simulated customer support ticket records with the following features:

- Ticket ID  
- Customer Age & Gender  
- Product Purchased  
- Ticket Type & Subject  
- Ticket Priority & Channel  
- Date of Purchase  
- Response Time & Resolution Time  
- Customer Satisfaction Rating (Target Variable)

---

## ⚙️ Tech Stack
- Python 🐍  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Scikit-learn  
- Jupyter Notebook  

---

## 🧹 Data Preprocessing
- Handled missing values  
- Removed irrelevant columns (Customer Name, Email, etc.)  
- Extracted date features:
  - Year  
  - Month  
  - Day  
- Encoded categorical variables using Label Encoding  

---

## 🔧 Feature Engineering
- Defined feature matrix (**X**) and target variable (**y**)  
- Split dataset into training and testing sets (70/30 ratio)  

---

## 📏 Feature Scaling
- Applied **StandardScaler** to normalize numerical features  
- Ensured all features contribute equally to model performance  

---

## 🤖 Model Building
- Model used: **Random Forest Classifier**  
- Trained on training dataset  
- Evaluated on test dataset  

---

## 📊 Model Evaluation
Model performance was evaluated using:

- Accuracy Score  
- Confusion Matrix  
- Classification Report  

---

## 🔥 Key Feature Insights
The most influential features affecting customer satisfaction:

- Ticket Priority  
- Response Time  
- Ticket Channel  

---

## 📈 Exploratory Data Analysis (EDA)
- Distribution of customer satisfaction ratings  
- Impact of ticket priority on ratings  
- Channel-wise behavior analysis  
- Age group-based trends  

---

## 🚀 Results
The model achieved good predictive performance and helps identify key drivers of customer satisfaction. This can help improve customer service operations and decision-making.

---

## 📌 Future Improvements
- Try advanced models like XGBoost or LightGBM  
- Perform hyperparameter tuning  
- Apply NLP on ticket descriptions  
- Deploy using Streamlit or Flask  

---

## 📂 Project Structure

customer-satisfaction-project/
│
├── data/
├── notebooks/
├── models/
├── images/
├── README.md
└── requirements.txt


---

## 🛠️ Installation & Usage

# Clone the repository
git clone https://github.com/unmeshup/customer-satisfaction-project.git

# Navigate into the project directory
cd customer-satisfaction-project

# Install dependencies
pip install -r requirements.txt

# Run Jupyter Notebook
jupyter notebook
