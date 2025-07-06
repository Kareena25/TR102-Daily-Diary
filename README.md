# TR102-Daily-Diary
My 4-week Smartfusion Training Daily Diary
# 📝 Daily Diary – Day 1  

*Date:* 25 June 2025  

### 📌 Topics Covered:
- Introduction to *IoT (Internet of Things)* and its real-life applications  
- Basic concepts of *Machine Learning (ML)* and *Artificial Intelligence (AI)*  
- Discussed *difference between IoT, ML, and AI* with examples  
- Explained *types of Machine Learning* – supervised, unsupervised, reinforcement  
- Introduction to *Arduino board* and its components like sensors, microcontroller, etc.  

### ✅ Task Given:
- Study and understand the concept of *Smart Umbrella* (IoT-based project)  
- Research and explore different simulators for practice

### 🔍 Key Learnings:
- Understood how IoT devices work in real life  
- Learned where and how ML and AI are used in smart systems  
- Gained basic knowledge of Arduino and Raspberry Pi  
- Explored the role of simulators in testing before hardware implementation
  
---

# 📅 Daily Diary – Day 2 

*Date:* 26 June 2025   

## 📘 Topics Covered:
- IoT architectural view and its 7 levels
- Introduction to sensors and smart sensors
- Introduction to actuators and smart actuators
- Overview of robotic systems and smart appliances

## 🧪 Simulators:
- Understood how IoT simulators work
- Learned how to test virtual connections

## 🔌 Hardware Connections:
- Connected LED, DHT11, and PIR motion sensor with Arduino
- Learned pin configuration and wiring setup

## 💻 Arduino Code:
- Arduino code explained for reading sensor data
- Understood how to simulate and upload code

## 🎯 Task Given:
- Write a code on simulator to read humidity and temperature using Arduino board and DHT11 sensor
- Install Anaconda on laptop
- Learn the difference between Arduino, NodeMCU, and Raspberry Pi

### 🔍 Key Learnings:
- Understood how IoT devices work in real life  
- Learned where and how ML and AI are used in smart systems  
- Gained basic knowledge of Arduino and Raspberry Pi  
- Explored the role of simulators in testing before hardware implementation

---

# ✍️ Daily Diary – Day 3

*Date:* 27 June 2025  

### 📚 Topics Covered  
- Introduction to Cloud Computing for IoT  
- Concepts of Traditional, Distributed, Cluster, Grid, and Cloud Computing  
- Client-Server Architecture and its role in IoT  
- Virtualization and its types  
- Cloud Deployment Models and Frameworks  
- Importance and benefits of Cloud Computing in IoT  
- Introduction to ThingSpeak platform  
- Steps to set up a ThingSpeak channel  
- Program to connect NodeMCU to Wi-Fi and read data from DHT11 sensor  

### ✅ Task Given  
- Explore platforms like Google App Engine, Microsoft Azure, and Amazon AWS  
- Read about Amazon EC2  
- Study IoT application platforms like ThingSpeak, Exhibly, Nimbit, and Cosm
- Completed the assignment based on IoT concepts explained during the session
- Started working on the IoT mini project as instructed by the faculty
 

### 💡 Key Learnings  
- Understood different types of computing in IoT context  
- Explored ThingSpeak as an IoT cloud platform  
- Understood benefits of using cloud for data storage and analysis

---

# 📝 Daily Diary – Day 4  

**📅 Date:** 30 June 2025  

## 📚 Topics Covered  
- Introduction to Data Acquisition in IoT  
- Sensor interfacing using ESP32 and DHT22  
- Reading temperature and humidity data using Arduino code  
- Connecting ESP32 to Wi-Fi (Wokwi simulation)  
- Sending sensor data to ThingSpeak using HTTP GET request  
- Viewing real-time data graphs on ThingSpeak  

## ✅ Task Given  
- Simulate ESP32 and DHT22 using Wokwi  
- Write code to acquire sensor data and send to ThingSpeak  
- Use API key and validate ThingSpeak channel data
- Observe the HTTP response and verify successful data upload

## 💡 Key Learnings  
- Understood the working of Data Acquisition in IoT systems  
- Gained hands-on experience with ESP32 and DHT22 sensor  
- Learned how to send data from hardware to cloud using HTTP request  
- Explored ThingSpeak as a real-time data visualization platform  
- Learned the practical use of API keys and response codes (like 200)  

---

# 📝 Daily Diary – Day 5  
**📅 Date:** 1 july 2025  

## 📚 Topics Covered  
- Overview of photoresistor (LDR) and light detection  
- Basics of interfacing servo motor with Arduino  
- Understanding analog input using LDR  
- Introduction to PWM (Pulse Width Modulation) for servo control  

## ✅ Task Given  
- Task 1: Detect light using a photoresistor (LDR)  
- Task 2: Interface a servo motor with Arduino and control its angle  

## 💡 Key Learnings  
- Learned how a photoresistor changes resistance based on light intensity  
- Understood how Arduino reads analog signals from LDR  
- Explored how servo motors work using PWM signals from Arduino  
- Got familiar with basic interfacing techniques of sensors and actuators  

---

# 📝 Daily Diary – Day 6  
**📅 Date:** 2 July 2025  

## 📚 Topics Covered  
- Introduction to **Data Preprocessing** in Machine Learning  
- Understanding **Train-Test Split** (80% training, 20% testing)  
- Key preprocessing techniques:
  - **Handling Missing Values** (NaN)
  - **Scaling** using MinMaxScaler  
  - **Normalization**   
- Installation of important Python libraries:
  - `pandas`
  - `numpy`
  - `scikit-learn`

## ✅ Task Given  
- Create a **CSV file** named `student_data.csv` including:
  - Columns: `Name`, `ID`, `Math`, `Science`, `English`  
  - 5–10 rows with some **missing values (NaN)** in the dataset  
- Load the dataset into a **pandas DataFrame**  
- Count missing values in each column using `df.isnull().sum()`  
- Handle missing values using:
  - **Mean**
  - **Median**
  - **Mode**  
- Display the updated cleaned dataset  
- Apply **MaxScaler** for feature scaling  
- Perform **Scaling**,**MinMax Scaler**, **Normalization** on numerical columns

## 💡 Key Learnings  
- Learned how to create and import CSV datasets  
- Understood how to detect and handle missing values in real-world data  
- Applied imputation techniques like **mean, median, mode**  
- Practiced data **scaling** to bring values in similar range  
- Used **normalization** to transform data into 0–1 scale  
- Explored and installed key ML libraries in Python (`pandas`, `numpy`, `sklearn`)

## 🛠️ Tools & Libraries Used  
- **Google Colab** / Jupyter Notebook  
- **Python 3.x**  
- Libraries: `pandas`, `numpy`, `scikit-learn`  
- File type: `.csv` for storing and loading tabular data

---

# 📝 Daily Diary – Day 7  
**📅 Date:** 3 July 2025  

## 📚 Topics Covered  

- **Introduction to Data Visualization**  
- Basics of `matplotlib.pyplot` and `seaborn` libraries  
- Common types of plots and graphs:
  - **Line Graph** using `plot()` function  
  - **Bar Graph**  
  - **Scatter Plot**  
  - **Histogram**  
  - **Pie Chart**  

- **Introduction to Seaborn Library**
  - Built on top of Matplotlib
  - Easier syntax and better visuals for statistical data

- **Advanced Seaborn Plots**
  - **Boxplot**, **Heatmap**
  - Using the built-in **`tips`** dataset
  - Functions: `sns.boxplot()`, `sns.heatmap()`, etc.

- **Real-Time Plotting**
  - Use of **`plt.ion()`** for interactive data visualization  
  - Enables live updates in graphs

## ✅ Task Given  

- **Read and understand** the concept of **real-time data plotting** using `plt.ion()`  
- Study the **`tips`** dataset used for plotting with Seaborn  
- Read about **Exploratory Data Analysis (EDA)** and its purpose

## 💡 Key Learnings  

- Gained theoretical understanding of various plot types  
- Understood how Seaborn simplifies visualization over Matplotlib  
- Learned about real-time plotting with `plt.ion()`  
- Explored the role of EDA in analyzing and understanding datasets

## 🛠️ Tools & Libraries Used  

- Python 3.x  
- **Matplotlib** → `import matplotlib.pyplot as plt`  
- **Seaborn** → `import seaborn as sns`  
- Dataset: **`tips`**  
- **Platform Used**: Kaggle Kernel  

---

# 📝 Daily Diary – Day 8  
**📅 Date:** 4 July 2025  

## 📚 Topics Covered  

- Recap and student explanations of **Exploratory Data Analysis (EDA)**  
- Discussion on the importance of EDA in Machine Learning  
- Key steps in EDA:  
  - Understanding data types  
  - Summary statistics  
  - Handling missing values  
  - Correlation and visualization  
- Real-time interaction and explanation by students (one-by-one)  

## 💻 Mini Project Discussion  

### 📌 Project Title:  
**Real-Time IoT Dashboard with Graphs**  

### 📊 What It Does:  
- Reads sensor data (e.g., temperature, light, humidity)  
- Sends data to cloud platform (like ThingSpeak)  
- Displays data in real-time on a custom dashboard using HTML/JavaScript  

### 📋 What Was Discussed:  
- Project goal and outcome  
- Tools used: ESP32, Wokwi, ThingSpeak, HTML/JS  
- Architecture overview of IoT system  
- **Flowchart** of data flow from sensor → ESP32 → Wi-Fi → ThingSpeak → Web Dashboard  

## ✅ Task Given  

- Prepare a brief overview of **EDA** and its steps  
- Study the **Real-Time IoT Dashboard with Graphs** project  
- Understand its implementation flow:  
  - Data collection  
  - Cloud communication  
  - Dashboard plotting  
- Sketch or refer to the **flowchart** showing system components and data path  

## 💡 Key Learnings  

- Understood how to **analyze datasets** using EDA for better insights  
- Learned the purpose and importance of EDA before applying ML models  
- Explored how IoT systems can visualize sensor data in real time  
- Learned about the **architecture of a cloud-connected IoT mini project**  
- Gained clarity on how dashboards are built using data and graphs  
