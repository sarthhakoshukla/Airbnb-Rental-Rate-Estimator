# 🏠 Airbnb Rental Rate Estimator  

This project predicts **Airbnb rental prices** based on various property features such as location, amenities, room type, and ratings.  
It combines **data preprocessing, exploratory data analysis (EDA), and regression modeling** to build an intelligent price estimator.  

---

## 📘 Project Overview  
This notebook analyzes and models Airbnb data to estimate rental prices more accurately.  
Key objectives:  
- Understand the relationship between features (like bedrooms, bathrooms, and reviews) and price.  
- Build a regression model that predicts rental prices.  
- Visualize insights for better understanding of pricing trends.  

---

## ⚙️ Tech Stack  
- **Python 3**  
- **Pandas**, **NumPy** – Data handling and cleaning  
- **Matplotlib**, **Seaborn** – Data visualization  
- **Scikit-learn** – Model building and evaluation  
- **Jupyter Notebook** – Analysis and presentation  

---

## 🧩 Workflow  

### 1️⃣ Data Loading  
Dataset is loaded and inspected for missing values, types, and distributions.

### 2️⃣ Data Preprocessing  
- Handling missing values  
- Encoding categorical variables  
- Scaling/normalizing numerical data  

### 3️⃣ Exploratory Data Analysis (EDA)  
- Visualized how different features (like bedrooms, bathrooms, and ratings) affect price  
- Found correlations between variables  

### 4️⃣ Model Building  
Tested and compared various regression models:  
- Linear Regression  
- Decision Tree Regressor  
- Random Forest Regressor  

### 5️⃣ Model Evaluation  
Evaluated performance using metrics such as:  
- R² Score  
- Mean Absolute Error (MAE)  
- Root Mean Squared Error (RMSE)  

---

## 📊 Key Insights  
- **Location and amenities** have the highest impact on rental prices.  
- **Number of bedrooms** and **ratings** also play major roles in determining price.  
- **Random Forest** performed best among tested models.  

---

## 🚀 How to Run  
```bash
# Clone this repository
git clone https://github.com/sarthhakoshukla/Airbnb-Rental-Rate-Estimator.git

# Go inside the folder
cd Airbnb-Rental-Rate-Estimator

# Run the Jupyter Notebook
jupyter notebook airbnb.ipynb
