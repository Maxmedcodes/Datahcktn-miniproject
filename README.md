# ✈️ Flight Price Analysis & Prediction

## 📌 Project Overview
This project uses a flight dataset to explore pricing trends and build a machine learning model that predicts flight prices based on factors like airline, departure time, number of stops, and days left before departure.  
The work was completed in **Databricks** using **Pandas**, **Matplotlib/Seaborn** for visualizations, and **Scikit-learn** for machine learning.

---

## 🎯 Objectives
- Perform **Exploratory Data Analysis (EDA)** to answer key business questions:
  1. How does the number of days left until departure affect the flight price?
  2. Do different airlines have significantly different average prices for the same routes?
  3. Does the number of stops impact both price and total travel time?
  4. Are morning, afternoon, or evening departures generally more expensive?
  5. Which destination cities have the highest average prices?
- Test hypotheses:
  - Flights booked closer to the departure date will have higher prices.
  - Flights with more stops will generally be cheaper than direct flights.
- Build a **machine learning regression model** to predict flight prices.

---

## 🗂 Dataset
**Columns used:**
- `airline` – Airline name  
- `flight` – Flight code  
- `source_city` – Departure city  
- `departure_time` – Time of departure (Morning/Afternoon/Evening/Night)  
- `stops` – Number of stops (zero, one, two)  
- `arrival_time` – Time of arrival  
- `destination_city` – Arrival city  
- `class` – Ticket class (Economy/Business)  
- `duration` – Total flight duration  
- `days_left` – Days between booking date and flight date  
- `price` – Ticket price (Target variable for ML)

---

## 📊 Exploratory Data Analysis
The following visualizations were created using **Matplotlib** and **Seaborn**:
1. **Price vs Days Left** – Scatter plot to check correlation.  
2. **Average Price by Airline** – Bar chart.  
3. **Price Distribution by Stops** – Boxplot.  
4. **Duration by Stops** – Boxplot.  
5. **Price by Departure Time** – Boxplot.  
6. **Top 10 Most Expensive Destinations** – Bar chart.

---

## 🤖 Machine Learning
A **Linear Regression** model was built using **Scikit-learn**.

### Steps:
1. Data preprocessing:
   - Selected relevant features
   - Converted categorical variables to numeric using one-hot encoding
2. Train/Test split (80% train, 20% test)
3. Model training with `LinearRegression()`
4. Evaluation using:
   - **R² Score**
   - **Mean Absolute Error (MAE)**
   - **Root Mean Squared Error (RMSE)**
5. Interpreted feature importance via model coefficients.

---

## 📈 Example Results
- **R² Score:** *~0.xx* (Varies by dataset)
- **MAE:** *~xxx currency units*
- **RMSE:** *~xxx currency units*
- Insights:
  - Price tends to **increase** as the departure date approaches.
  - Direct flights are generally more expensive than flights with stops.
  - Certain airlines consistently charge higher prices for the same routes.

---

## 🛠 Tech Stack
- **Databricks** – Notebook environment
- **Python 3**  
- **Pandas** – Data manipulation  
- **Matplotlib / Seaborn** – Visualization  
- **Scikit-learn** – Machine learning  

---

## 📌 How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/Maxmedcodes/Datahcktn-miniproject
