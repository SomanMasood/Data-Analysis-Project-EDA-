# ✈️ Flight Price Analysis & Prediction

## 📌 Project Overview
This project performs an end-to-end analysis of flight pricing data to understand the key factors influencing ticket prices and to build predictive models for estimating flight fares.

The focus is on **exploratory data analysis (EDA)**, **feature engineering**, **categorical encoding**, and **model interpretation**, rather than just model accuracy.  
The project reflects a real-world data analyst workflow from raw data to business insights.

---

## 🎯 Objective
- Analyze historical flight price data
- Identify major drivers of flight ticket prices
- Build regression models to predict prices
- Interpret model results to extract business-relevant insights

---

## 📂 Dataset
The dataset contains flight booking information with features such as:
- Airline
- Source city
- Destination city
- Date of journey
- Number of stops
- Flight duration
- Ticket price (target variable)

The dataset is stored locally in the `data/` directory and loaded using relative paths for portability.

---

## 🔍 Key Steps in the Analysis
1. **Data Loading & Inspection**
   - Dataset structure, data types, and summary statistics

2. **Exploratory Data Analysis (EDA)**
   - Price distribution analysis
   - Airline-wise pricing patterns
   - Effect of stops and routes on ticket prices

3. **Feature Engineering**
   - Extracting day and month from journey date
   - Parsing duration into numerical features
   - Handling ordinal and nominal variables appropriately

4. **Encoding Strategy**
   - One-hot encoding for nominal categorical features
   - Preserving ordinal meaning where applicable

5. **Modeling**
   - Linear Regression as a baseline model
   - Random Forest Regressor for capturing non-linear relationships

6. **Feature Importance Analysis**
   - Identifying key variables influencing flight prices
   - Translating model outputs into business insights

---

## 📊 Key Insights
- The **number of stops** is the strongest determinant of flight prices; direct flights consistently cost more.
- **Airline choice** significantly affects pricing, reflecting brand and service premiums.
- **Route-specific factors** influence prices as much as, and sometimes more than, airline selection.
- Tree-based models outperform linear models by capturing non-linear pricing behavior.

---

## ⚠️ Limitations
- The analysis is based on historical data and does not include real-time demand fluctuations.
- External factors such as fuel prices, holidays, promotions, and seat availability are not captured.
- Feature importance reflects correlation patterns, not causal relationships.

---

## 🛠️ Tools & Libraries
- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn
- Jupyter Notebook

---

## ▶️ How to Run the Project
1. Clone the repository:
   ```bash
   git clone https://github.com/SomanMasood/Data-Analysis-Project-EDA-.git
