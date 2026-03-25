# 🛒 Blinkit Sales Analysis & Prediction

## 📌 Objective

The goal of this project is to understand how different factors affect sales in a retail dataset and to build a simple model that can predict sales.

---

## 📊 About the Dataset

The dataset contains around **8500+ records** with information about:

* Products (type, fat content, visibility, weight)
* Outlets (type, size, location, year)
* Sales and ratings

---

## 🧹 Data Cleaning

Before analysis, the data was cleaned to ensure accuracy:

* Filled missing values in **Item Weight**
* Standardized **Item Fat Content** values
* Fixed incorrect zero values in **Item Visibility**
* Removed unnecessary ID columns

---

## ⚙️ Feature Engineering

* Created a new column **Outlet Age** from the establishment year
* This helps better understand how outlet experience affects sales

---

## 📈 Analysis & Visualizations

I explored the data using different charts to understand patterns:

* Sales by product category
* Sales by outlet type
* Distribution of sales
* Comparison of low-fat vs regular products

---

## 🧠 Key Findings

* A few product categories generate most of the sales
* Low-fat products contribute a larger share of revenue
* Product visibility plays a major role in sales
* Highly rated products tend to perform better

---

## 🤖 Machine Learning

A **Random Forest model** was used to predict sales.

**Results:**

* R² Score: ~0.54
* MAE: ~31

👉 The model performs moderately well, capturing some patterns but still has room for improvement.

---

## 📊 Feature Importance

The model shows that:

* Product visibility is the most important factor
* Item type and weight also impact sales
* Outlet-related features have less influence

---

## ⚠️ Limitations

* No data on pricing or discounts
* External factors like competition are not included
* Model can be improved further

---

## 🚀 Future Improvements

* Improve model accuracy with tuning
* Build an interactive dashboard
* Add more business-related features

---

## 🛠️ Tools Used

* Python
* Pandas
* Matplotlib & Seaborn
* Scikit-learn

 project link https://github.com/amanahmad11/blinkit-project-python-ML/blob/main/blinkit%20project.ipynb
 
 ---

## 💼 Conclusion

This project shows how data analysis and machine learning can help understand sales patterns and support better decision-making. It highlights the importance of product visibility and customer preferences in driving sales.

---
