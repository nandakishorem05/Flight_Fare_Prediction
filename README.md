# Flight_Fare_Prediction
A data science project that predicts flight ticket prices using machine learning algorithms and historical flight data.

# ✈️ Flight Fare Prediction

## 📌 Project Overview

Flight ticket prices change frequently depending on multiple factors such as airline, departure time, destination, and number of stops.
This project uses **Machine Learning** to predict flight ticket prices based on historical flight data.

The goal is to build a predictive model that helps estimate the **approximate fare of a flight**.

---

## 📊 Dataset

The dataset contains information about flights such as:

* Airline
* Date of Journey
* Source
* Destination
* Route
* Departure Time
* Arrival Time
* Duration
* Total Stops
* Additional Info
* Price (Target Variable)

---

## 🧠 Machine Learning Models Used

The following models were implemented and tested:

* Decision Tree Regressor
* Random Forest Regressor

Hyperparameter tuning was performed using **GridSearchCV** to improve model performance.

---

## ⚙️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook

---

## 🔍 Project Workflow

1. Data Collection
2. Data Cleaning
3. Feature Engineering
4. Exploratory Data Analysis (EDA)
5. Model Training
6. Hyperparameter Tuning
7. Model Evaluation
8. Saving the trained model

---

## 📈 Model Evaluation

The model performance was evaluated using:

* Mean Absolute Error (MAE)
* Mean Squared Error (MSE)
* R² Score

Random Forest Regressor provided the **best prediction accuracy**.

---

## 📂 Project Structure

```
Flight_Fare_Prediction
│
├── Flight_price_pred.ipynb   # Data analysis and model training
├── Flight_Fare.xlsx          # Dataset
├── model.pkl                 # Saved machine learning model
└── README.md                 # Project documentation
```

---

## 🚀 How to Run the Project

### 1️⃣ Clone the Repository

```
git clone https://github.com/yourusername/Flight_Fare_Prediction.git
```

### 2️⃣ Install Required Libraries

```
pip install pandas numpy matplotlib seaborn scikit-learn
```

### 3️⃣ Run the Notebook

```
jupyter notebook Flight_price_pred.ipynb
```

---

## 📊 Example Insights

* Airline choice significantly affects ticket price.
* Flights with more stops generally have lower prices.
* Travel time and departure time influence the fare.

---

## 🔮 Future Improvements

* Deploy the model using **Flask or Streamlit**
* Create a **web interface for fare prediction**
* Use advanced algorithms like **XGBoost**

---

## 👨‍💻 Author

**Nandakishore M**

Data Science Enthusiast

GitHub: https://github.com/nandakishorem05


