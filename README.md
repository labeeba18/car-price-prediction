# car-price-prediction

# 🚗 Car Price Prediction using Machine Learning

## 📌 Project Overview
The price of a car depends on many factors such as brand value, features, horsepower, mileage, fuel type, transmission, and year of manufacture.  
Car price prediction is an important research area in machine learning with real-world applications in the automobile and resale industry.

In this project, we build a **machine learning model** that predicts the **selling price of a car** based on historical data.

---

## 🎯 Objective
- Understand the factors affecting car prices
- Perform data preprocessing and analysis
- Train a machine learning regression model
- Evaluate the model’s performance
- Gain hands-on experience with the complete ML workflow

---

## 📂 Dataset Information
- **Source:** Kaggle – Car Price Prediction Dataset  
- **File Format:** CSV  
- **Target Variable:** `Selling_Price`

### Dataset Features
- `Car_Name` – Name of the car  
- `Year` – Year of manufacture  
- `Selling_Price` – Selling price of the car (Target)  
- `Present_Price` – Current showroom price  
- `Kms_Driven` – Distance driven  
- `Fuel_Type` – Petrol / Diesel / CNG  
- `Seller_Type` – Dealer or Individual  
- `Transmission` – Manual or Automatic  
- `Owner` – Number of previous owners  

---

## 🛠 Tools & Technologies Used
- **Programming Language:** Python  
- **IDE:** VS Code, Jupyter Notebook  
- **Libraries Used:**
  - NumPy
  - Pandas
  - Matplotlib
  - Seaborn
  - Scikit-learn

---

## 🔄 Project Workflow (Step-by-Step)

### 1️⃣ Problem Statement
Define the goal of predicting car prices based on multiple influencing factors using machine learning techniques.

---

### 2️⃣ Dataset Loading
The dataset is loaded into a Pandas DataFrame for easy manipulation and analysis.

---

### 3️⃣ Importing Required Libraries
Essential Python libraries are imported for:
- Data handling
- Visualization
- Model training and evaluation

---

### 4️⃣ Data Preprocessing
In this step:
- Missing values are checked
- Unnecessary columns are removed
- A new feature **Car Age** is created from the year column
- Categorical variables are prepared for modeling

---

### 5️⃣ Exploratory Data Analysis (EDA)
EDA is performed to:
- Understand price distribution
- Analyze relationships between price and features
- Identify important variables affecting car prices

Visualizations help in better understanding the dataset.

---

### 6️⃣ Model Training
A **Linear Regression** model is used to train the dataset.  
The model learns the relationship between independent features and the selling price.

---

### 7️⃣ Model Evaluation
The model is evaluated using the **R² score**, which measures how well the predicted values match the actual values.

A higher R² score indicates better model performance.

---

### 8️⃣ Conclusion
- The model successfully predicts car prices with good accuracy
- Features such as **present price**, **car age**, and **fuel type** have a strong influence
- This project demonstrates an end-to-end machine learning workflow

---

## 📈 Results
- Accurate prediction of car selling prices
- Clear understanding of important price-influencing factors
- Suitable for beginner-level machine learning practice

---

## 🚀 Future Enhancements
- Use advanced models like Random Forest or XGBoost
- Improve performance with hyperparameter tuning
- Deploy the model using Flask or Streamlit
- Add more real-world datasets

---

## 👩‍💻 Author
**Labeeba Aafeen**  
_Data Science & Machine Learning Enthusiast_

---

## ⭐ Acknowledgment
Thanks to Kaggle for providing the dataset and open-source contributors for the libraries used in this project.