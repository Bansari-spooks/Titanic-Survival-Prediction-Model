# 🚢 Titanic Survival Prediction

A machine learning project that predicts whether a Titanic passenger would **survive or not survive** based on passenger information such as class, gender, age, family members, fare, and embarkation port.

The project uses **Logistic Regression** for binary classification and includes data preprocessing, exploratory data analysis, model evaluation, and an interactive **Streamlit web application**.

---

## ✅ Features

* 🚢 Predicts passenger survival
* 🤖 Uses Logistic Regression for classification
* 🧹 Handles missing values and categorical features
* 📊 Includes Exploratory Data Analysis (EDA)
* 📈 Evaluates model performance using multiple metrics
* 📐 Includes ROC-AUC analysis
* 💾 Saves the trained model using Pickle
* 🌐 Interactive Streamlit prediction interface
* 🎯 Displays prediction probability

---

## 🧠 How It Works

The system follows a simple machine learning workflow:

**Dataset → Data Preprocessing → Feature Engineering → Train/Test Split → Logistic Regression → Model Evaluation → Streamlit Prediction**

The model uses the following features:

* Passenger Class
* Sex
* Age
* Siblings/Spouses
* Parents/Children
* Fare
* Embarkation Port

---

## 📊 Model Performance

The model was evaluated on a held-out test dataset using an 80/20 train-test split.

| Metric            |  Score |
| ----------------- | -----: |
| Training Accuracy | 80.00% |
| Test Accuracy     | 81.01% |
| Precision         | 78.57% |
| Recall            | 74.32% |
| F1 Score          | 76.39% |
| ROC-AUC           | 88.25% |

---

## 🌐 Streamlit Application

The trained model is integrated into a Streamlit web application where users can enter passenger details and receive:

* **Survival Prediction**
* **Survival Probability**

The application provides a simple interface for interacting with the trained machine learning model.

---

## 🛠️ Technologies Used

| Technology               | Purpose              |
| ------------------------ | -------------------- |
| **Python**               | Programming          |
| **Pandas**               | Data Processing      |
| **NumPy**                | Numerical Operations |
| **Scikit-learn**         | Machine Learning     |
| **Matplotlib & Seaborn** | Data Visualization   |
| **Streamlit**            | Web Application      |
| **Pickle**               | Model Serialization  |
| **Jupyter Notebook**     | Model Development    |

---

## 📁 Project Structure

```text
Titanic_Project/
│
├── app.py
├── code.ipynb
├── model.pkl
├── Titanic_train.csv
├── Titanic_test.csv
├── requirements.txt
└── README.md
```

---

## ⚙️ How to Run

### 1. Clone the Repository

Clone the project from GitHub and open the project directory.

### 2. Install Dependencies

Install the required packages using the provided `requirements.txt` file.

### 3. Run the Application

Launch the Streamlit application and open the provided local URL in your browser.

---

## 🎓 Concepts Demonstrated

* Supervised Machine Learning
* Binary Classification
* Logistic Regression
* Data Preprocessing
* Exploratory Data Analysis
* Feature Engineering
* Model Evaluation
* ROC-AUC Analysis
* Model Serialization
* Streamlit Deployment

---

## 🚀 Future Improvements

* Compare multiple classification algorithms
* Add cross-validation and hyperparameter tuning
* Add interactive model-performance visualizations
* Improve input validation
* Deploy the application online
* Build a complete preprocessing and prediction pipeline

---

## 👨‍💻 Author

**BANSARI NIMBALKAR**

Computer Science / Data Science Graduate

**Project:** Titanic Survival Prediction — Machine Learning & Streamlit

---

⭐ If you found this project useful, consider giving the repository a star.
