
## 📌 Project Overview  
This project focuses on performing **Exploratory Data Analysis (EDA)** on the Divvy Bike-Share dataset for April 2020 (Chicago).  
The goal is to analyze user behavior patterns between **annual members** and **casual riders** to derive actionable business insights.

---

## 📂 Dataset Details  
- **File:** 202004-divvy-tripdata.csv  
- **Total Records:** 84,775  
- **Cleaned Records:** 84,717  
- **Columns:** 14  
- **Date Range:** April 1 – April 30, 2020  

---

## 🛠️ Tools & Technologies  
- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Jupyter Notebook  

---

## 🧹 Data Cleaning Steps  
- Converted `started_at` and `ended_at` to datetime format  
- Created `ride_length` column (in minutes)  
- Removed invalid rides (≤ 0 minutes)  
- Extracted:
  - Day of Week  
  - Month  
  - Hour  

---

## 📊 Exploratory Data Analysis  

### 1️⃣ User Distribution  
- Members: **61,112 (~72%)**  
- Casual Riders: **23,605 (~28%)**  

👉 Members dominate the platform usage  

---

### 2️⃣ Average Ride Length  
- Members: **~21.5 minutes**  
- Casual Riders: **~73.1 minutes**  

👉 Casual riders take **3.4x longer rides**  

---

### 3️⃣ Hourly Usage Patterns  
- Members peak during:  
  - **Morning:** 7–9 AM  
  - **Evening:** 4–6 PM  
- Casual riders peak during:  
  - **Midday:** 10 AM – 3 PM  

👉 Clear **commute vs leisure behavior**  

---

### 4️⃣ Day-of-Week Analysis  
- Highest rides on **Sunday**  
- Members → consistent weekday usage  
- Casual → weekend spikes  

👉 Casual users are more leisure-oriented  

---

## 🔍 Key Insights  
✔ Members are the core users (majority usage)  
✔ Casual riders prefer long, leisure trips  
✔ Strong weekday commute pattern for members  
✔ Weekend demand driven by casual users  
✔ Opportunity to convert casual → members  

---

## 💡 Business Recommendations  
- Introduce **weekend promotions** for casual riders  
- Provide **membership discounts** to frequent casual users  
- Optimize bike availability during peak commute hours  
- Design targeted campaigns based on user behavior  

---

## 📁 Project Structure  
Divvy-Bike-EDA
┣ 📜 divvy_eda.ipynb
┣ 📜 cleaned_data.csv
┣ 📜 README.md

---

## 🚀 How to Run  

1. Clone the repository  
```bash
https://github.com/Gargeya15/Divvy-Bike-Share-EDA/tree/main
Install dependencies
pip install pandas numpy matplotlib seaborn
Run Jupyter Notebook
jupyter notebook

