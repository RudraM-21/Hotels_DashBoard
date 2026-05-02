# 🏨 Hotel Revenue & Booking Insights Dashboard

An end-to-end data engineering and business intelligence project designed to extract, transform, and visualize hotel performance metrics. This repository contains the complete pipeline—from Python-based ETL and relational database design to a fully interactive Power BI dashboard—enabling stakeholders to make data-driven decisions on revenue, occupancy, and booking trends.

---

## 📌 Project Overview

The hospitality industry relies heavily on understanding key performance indicators such as:

- **RevPAR** (Revenue Per Available Room)  
- **ADR** (Average Daily Rate)  
- **Occupancy Rate**  
- **Realized Revenue**

This project processes hotel operational data through a structured ETL pipeline and converts it into actionable insights via:

- **Extraction & Transformation:** Python (`Pandas`, `NumPy`) for cleaning and preprocessing  
- **Database Design:** MySQL schema with primary/foreign keys and optimized queries  
- **Business Intelligence:** Interactive Power BI dashboard for insights  

---

## 🛠️ Tech Stack & Architecture

- **Data Processing & ETL:** Python, Pandas, NumPy, SQLAlchemy  
- **Database:** MySQL  
- **Visualization:** Power BI  
- **Tools:** Jupyter Notebook, VS Code  

### 🔄 Data Pipeline


Raw CSV Data → Python ETL → MySQL Database → Power BI Dashboard


---

## 📁 Repository Structure


├── data/ # Raw datasets
├── main.ipynb # ETL pipeline notebook
├── data_transformation.sql # SQL schema & constraints
├── EER diagram.pdf # Database design diagram
├── Hotels_Data_Revenue_Insights.pbix # Power BI dashboard
├── requirements.txt # Dependencies
└── README.md # Documentation


---

## 🏗️ Database Design (Star Schema)

The project uses a **Star Schema** for optimized analytical queries.

### 📊 Fact Tables
- **fact_bookings:**  
  Stores booking-level data including revenue, dates, and platform details  

- **fact_aggregated_bookings:**  
  Stores aggregated metrics like total bookings and capacity  

### 🗂️ Dimension Tables
- **dim_hotels:** Hotel details (name, category, city)  
- **dim_rooms:** Room categories (Elite, Standard, etc.)  
- **dim_date:** Date-based features (month, week, weekday/weekend)  

---

