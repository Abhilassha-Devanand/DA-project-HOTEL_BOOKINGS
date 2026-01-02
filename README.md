# DA-project-HOTEL_BOOKINGS
# 🏨 Hotel Booking Data Analysis

## 📌 Project Overview
This project performs end-to-end data analysis on hotel booking data to uncover insights related to booking behavior, cancellations, pricing trends, and seasonality. The project follows a professional analytics workflow, starting from raw data cleaning to exploratory data analysis (EDA) and visualization using Python.

---

## 🎯 Objectives
- Clean and preprocess raw hotel booking data
- Handle missing values and invalid records appropriately
- Perform exploratory data analysis to identify patterns and trends
- Visualize key insights related to cancellations, pricing, and customer segments
- Build a reproducible, recruiter-ready analytics project

---

## 🗂️ Project Structure
Hotel-Booking-Analysis/
│
├── hotel_bookings.csv # Raw dataset
├── hotel_bookings_cleaned.csv # Cleaned dataset
├── Hotel_bookings_dataclean.ipynb # Data cleaning & preprocessing
├── EDA and Data Visual.ipynb # Exploratory Data Analysis & Visualizations
└── README.md
---

## 📊 Dataset Description
The dataset contains booking information for city and resort hotels, including booking dates, guest details, pricing (ADR), market segments, cancellations, and length of stay.

---

## 🧹 Data Cleaning & Preprocessing
Data cleaning was performed using Python (Pandas) in a separate notebook.

Key steps:
- Handled missing values in children, country, agent, and company columns
- Removed duplicate records
- Removed invalid bookings with zero guests
- Removed negative ADR values
- Standardized categorical data
- Saved the cleaned dataset as a separate CSV file

The cleaned dataset is stored as `hotel_bookings_cleaned.csv`.

---

## 🔍 Exploratory Data Analysis (EDA)
EDA was conducted using Python and Matplotlib on the cleaned dataset.

Key analyses:
- Booking cancellation distribution
- Average Daily Rate (ADR) by hotel type
- Monthly booking trends
- Market segment distribution
- Lead time vs ADR analysis
- Length of stay vs cancellation behavior
- Guest composition analysis

Each visualization is supported by business-relevant insights.

---

## 📈 Tools & Technologies
- Python
- Pandas
- Matplotlib
- Jupyter Notebook

---

## 💡 Key Insights
- City hotels generally have higher ADR compared to resort hotels
- Online Travel Agents (OTAs) dominate the booking channels
- Longer booking lead times are often associated with lower prices
- Cancellation behavior shows identifiable patterns
- Booking demand varies significantly across seasons

---

## 🧠 Project Workflow
Raw Data (CSV)
↓
Data Cleaning & Preprocessing (Python)
↓
Cleaned Dataset (CSV)
↓
Exploratory Data Analysis & Visualization (Python)

yaml
Copy code

---

## 🚀 Conclusion
This project demonstrates the ability to clean real-world data, perform structured exploratory data analysis, and extract meaningful business insights using Python. It follows industry-standard analytics practices and is suitable for Data Analyst fresher or junior roles.

---

## 📌 Future Enhancements
- Build an interactive dashboard using Power BI
- Add business KPIs such as cancellation rate and revenue metrics
- Perform predictive analysis on booking cancellations

---

## 👤 Author
Abhilassha D
