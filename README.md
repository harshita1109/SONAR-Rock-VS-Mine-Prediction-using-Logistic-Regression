# 🐬 SONAR Rock vs Mine Classifier 🎯
### Logistic Regression Based Binary Classification

<p align="center">
  <img src="https://img.icons8.com/color/96/submarine.png" alt="Sonar Logo"/>
</p>

---

## 📌 Project Overview
This project implements a **SONAR Rock vs Mine Classifier** using **Logistic Regression**.  
The model analyzes sonar signal frequency data to accurately distinguish between **underwater rocks (R)** and **mines (M)**.

---

## 🧠 Problem Statement
Sonar systems emit sound waves and analyze reflections.  
The challenge is to **classify objects** detected underwater as:
- 🪨 **Rock**
- 💣 **Mine**

This is a **binary classification problem** solved using **Machine Learning**.

---

## 🗂 Dataset Information
- 📊 **Dataset**: Sonar Dataset (UCI ML Repository)
- 🔢 **Features**: 60 continuous numerical attributes
- 🎯 **Target**:  
  - `R` → Rock  
  - `M` → Mine  

---

## ⚙️ Tech Stack & Tools
- 🐍 Python  
- 📦 NumPy, Pandas  
- 📊 Matplotlib, Seaborn  
- 🤖 Scikit-learn  

---

## 🔄 Workflow
1. 📥 Load SONAR dataset  
2. 🧹 Data inspection & outlier visualization  
3. ⚖️ Feature scaling using **StandardScaler**  
4. 🔀 Train-test split  
5. 🧠 Model training with **Logistic Regression**  
6. 📈 Model evaluation (Accuracy)  
7. 🔮 Predictions on unseen data  

---

## 🧪 Model Used
### 🔹 Logistic Regression
- Suitable for binary classification
- Uses **sigmoid function**
- Optimized using gradient descent
- Regularization helps prevent overfitting

---

## 📊 Results
- ✅ Model trained successfully
- 📈 Achieved good classification accuracy
- 🔍 Capable of predicting unseen sonar signals

---

## 🔮 Sample Prediction
```python
prediction = model.predict(unseen_scaled_sample)
print(prediction)

🚀How to run the project

Clone the repository

git clone https://github.com/your-username/sonar-rock-vs-mine.git


Install dependencies

pip install numpy pandas matplotlib seaborn scikit-learn


Run the Python script / Notebook

📁 Project Structure
├── sonar_(rock_vs_mine)_logr.py
├── SONAR_Rock_vs_Mine_LogR.ipynb
├── Copy of sonar data.csv
└── README.md

🎯 Key Learnings

Importance of feature scaling

Handling real-world numeric datasets

Logistic Regression for binary classification

Making predictions on unseen data

🤝 Contributing

Contributions, suggestions, and improvements are welcome!
Feel free to fork the repository ⭐

📜 License

This project is for educational purposes.
