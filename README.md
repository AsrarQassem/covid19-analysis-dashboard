
# COVID-19 Interactive Dashboard & Predictor  
An interactive COVID-19 data analysis dashboard and predictive modeling system built using Hadoop, Spark, Hive, and machine learning. The project visualizes global COVID-19 trends, processes large-scale datasets, and forecasts future case counts using regression algorithms.

---

## 🧪 Technical Summary
This system processes large COVID-19 datasets using Hadoop and Spark, visualizes key global statistics in an interactive dashboard, and predicts future case counts through a machine learning regression model. It combines distributed storage, fast data processing, and real-time data exploration to support insights into pandemic trends.

---

## 📖 Introduction
The COVID-19 pandemic produced massive volumes of data, making it difficult for the public and policymakers to interpret ongoing trends. This project addresses that challenge by creating a real-time interactive dashboard that displays global and country-specific COVID-19 statistics. It uses Hadoop HDFS, Hive, and Spark to store, clean, and process large datasets while employing supervised learning (linear regression) to predict future COVID-19 cases.

The dashboard provides a user-friendly interface with charts, graphs, and maps that simplify complex data. Predictions help anticipate upcoming spikes or waves, supporting decision-making for healthcare organizations, researchers, and the public.

---

## ✨ Features

### **Interactive Visualizations**
- Global and country-level COVID-19 statistics  
- Confirmed, recovered, and death cases  
- Line charts, bar graphs, and geographic heatmaps  

### **Prediction Model**
- Machine learning regression model  
- Forecasts future COVID-19 cases  
- Helps detect early signs of future waves  

### **Big Data Processing**
- Hadoop HDFS for distributed data storage  
- MapReduce for processing large datasets  
- Spark & Spark MLlib for fast analytics and machine learning  

### **Data Cleaning & Transformation**
- Hive for data preprocessing, querying, and structuring  
- Converts raw/unstructured data into clean analytical formats  

### **User-Friendly Dashboard**
- Intuitive and simple interface  
- Visual insights for both technical and non-technical users  
- Continuously updateable with new datasets  

---

## 🧰 Tech Stack

### **Big Data Technologies**
- Hadoop HDFS  
- Hadoop MapReduce  
- Apache Hive  
- Apache Spark  
- Spark MLlib  

### **Machine Learning**
- Linear Regression  
- Supervised Learning  

### **Data Source**
- Johns Hopkins University CSSE COVID-19 Dataset  

### **Visualization / Dashboard Technologies**
- Python  
- Pandas, NumPy  
- Matplotlib / Seaborn  
- (Or any dashboard framework used: Streamlit, Flask, custom UI)

---

## ⚙️ Installation

### **Prerequisites**
Ensure the following are installed:
- Hadoop  
- Hive  
- Apache Spark  
- Python 3.x  
- Python libraries:

  * pandas  
  * numpy  
  * matplotlib  
  * seaborn  
  * pyspark  
---

## 🗺️ Architecture Overview

**HDFS → Hive → Spark Processing → ML Model → Dashboard Visualization**

### **1️⃣ HDFS – Data Storage**
HDFS stores large COVID-19 datasets and provides a distributed file system capable of handling big data efficiently.

### **2️⃣ Hive – Data Cleaning & Structuring**
Hive cleans, transforms, and structures the raw dataset. It converts unstructured CSV files into queryable tables using SQL-like commands.

### **3️⃣ Spark – Big Data Processing**
Spark reads the cleaned data from Hive/HDFS and processes it using fast, distributed computing. It prepares the dataset for analytics and machine learning.

### **4️⃣ Spark MLlib – Machine Learning Model**
Spark MLlib trains the regression-based machine learning model to predict future COVID-19 case counts.

### **5️⃣ Dashboard – Visualization Layer**
The dashboard visualizes processed data and prediction results using charts, graphs, and maps, making insights accessible to technical and non-technical users.

---

## 🚀 Usage

### **View the Dashboard**
- Launch the Python dashboard script  
- Open the browser at the provided local URL  
- Explore COVID-19 statistics via charts, graphs, and maps  

### **Run Predictions**
- Enter the number of future days to forecast  
- The regression model outputs predicted case counts  
- Visual and numeric results help detect trends  

### **Updating Data**
- Upload newly downloaded data into HDFS  
- Re-run Spark processing and prediction scripts  
- Dashboard automatically updates with refreshed results  


