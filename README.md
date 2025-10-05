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

---

# 📝 Daily Diary – Day 9  
**📅 Date:** 7 July 2025  

## 📚 Topics Covered  

### 🔹 Introduction to Machine Learning  
- Definition and importance of Machine Learning  
- Comparison: Traditional Programming vs. Machine Learning  
- Difference between AI, ML, and Deep Learning  
- Training Phase vs. Testing Phase  

### 🔹 Types of Machine Learning  

#### ✅ Supervised Learning  
- Input and output labeled data  
- Concepts:  
  - **Classification**: Predicting categories (e.g., spam or not spam)  
  - **Regression**: Predicting continuous values (e.g., house price)  

#### ✅ Unsupervised Learning  
- Input data without labels  
- Concepts:  
  - **Clustering**: Grouping similar data (e.g., customer segmentation)  
  - **Association**: Discovering relationships (e.g., Market Basket Analysis)  

#### ✅ Reinforcement Learning  
- Learning from environment using rewards and penalties  
- Applications: Gaming, Robotics, Navigation systems  

### 🔹 Algorithms and Concepts  

#### 📈 Regression Analysis  
- **Linear Regression**  
- **Logistic Regression**  
- **Support Vector Machines (SVM)**  
- **Decision Tree**  
- **Random Forest**

#### 🧠 Classification Algorithms  
- Difference: Regression vs Classification  
- Graph-based explanation using examples  

#### 📊 Unsupervised Algorithms  
- K-Means Clustering  
- K-NN (K-Nearest Neighbors)  
- Hierarchical Clustering  
- Anomaly Detection  
- Principal Component Analysis (PCA)  
- Apriori Algorithm  

#### 🧠 Neural Networks  
- Basic intro and connection to deep learning  

## ✅ Task Given  

- Write the **difference between Supervised, Unsupervised, and Reinforcement Learning**  
- Understand Linear Regression Algorithm  
  - Apply Linear Regression with an example  
  - Calculate **Mean Squared Error (MSE)**  
  - Understand **residuals** in regression  

## 💡 Key Learnings  

- Understood how ML differs from traditional programming  
- Learned about 3 types of ML: Supervised, Unsupervised, Reinforcement  
- Gained clarity on various ML algorithms and their applications  
- Practically explored Linear Regression with error analysis    
- Explored multiple unsupervised learning techniques like clustering

---

# 📘 Daily Diary – Day 10
**📅 Date:** 8 July 2025  

## 📚 Topic: K-Means Clustering Algorithm & Smart City Case Study (Ludhiana)  

## 🔍 Topics Covered

### 🔹 K-Means Clustering Algorithm
- **Type:** Unsupervised Machine Learning Algorithm
- **Purpose:** To group similar data points into *K clusters* without using labeled data.
- **Applications:** 
  - Customer Segmentation  
  - Image Compression  
  - Market Basket Analysis  
  - Urban Zone Classification  

## ⚙️ Working Steps of K-Means Algorithm

1. Select the number of clusters, `K`.
2. Randomly initialize `K` centroids.
3. Assign each data point to the **nearest centroid** using Euclidean distance.
4. Recalculate the centroids by averaging the points assigned to each cluster.
5. Repeat steps 3 and 4 until the centroids do not change significantly (i.e., convergence is reached).

## 🧠 Additional Concepts Discussed

### 🔸 Online Learning
- Model learns **continuously** as new data comes in.
- Ideal for real-time systems (e.g., recommendation engines, fraud detection).

### 🔸 Semi-Supervised Learning
- Uses a small amount of **labeled data** with a large amount of **unlabeled data**.
- Reduces labeling effort and cost.
- Useful when labeled data is expensive or limited.

## 🧪 Hands-On Activity

**🧾 Task Given:**  
Use the K-Means Clustering algorithm to classify unlabeled data points into different clusters.  

**🎯 Objective:**  
- Practice how K-Means automatically separates data into groups based on similarity.
- Visualize how centroids are updated after each iteration.

## 🏙️ Case Study: Smart City Project – Ludhiana

### 📝 Task:
Study the **current status of Ludhiana** under the Smart City initiative and apply ML techniques like K-Means Clustering to identify zones for improvement.

### 📌 Observations from Current Scenario:
- 🚦 Traffic congestion during peak hours.
- 🗑️ Waste collection systems are semi-automated but not consistent across zones.
- 🌫️ High air pollution in industrial regions.
- 🚍 Public transport digitization is ongoing but not fully adopted.

## ✅ Learning Outcome

- Understood the theory and working steps of the **K-Means Clustering Algorithm**.
- Learned about **Online Learning** and **Semi-Supervised Learning** in ML.
- Explored a **real-world problem (Smart City – Ludhiana)** and thought about how ML can help solve urban issues.
- Strengthened understanding of **unsupervised learning techniques** through hands-on practice and real-world case study.

---

## 📅 Daily Diary - Day 11
**Date :** 9 july 2025

### ✅ Topics Covered
- K-Nearest Neighbors (KNN) Algorithm  
- How to choose the right algorithm for ML projects  
- Concept of Confusion Matrix  
- Accuracy & Precision Formula  
- Project Title Finalization & Objective Writing  

### 📘 Key Learnings
- KNN is used for classification based on nearest data points  
- Steps: Choose K, calculate distances, pick K nearest, assign most common class  
- KNN is simple and works well for small datasets  
- Confusion Matrix is useful to evaluate classification performance  
- Accuracy = (TP + TN) / (TP + TN + FP + FN)  
- Precision = TP / (TP + FP)  
- Choice of algorithm depends on data type, dataset size, and project needs  

### 🔧 Tools / Platforms Used
- Python (scikit-learn)  
- Colab / Jupyter Notebook  

### 🧪 Tasks Performed
- Learned KNN working with real datasets  
- Compared ML algorithms for our ML + IoT project  
- Discussed confusion matrix in detail  
- Finalized project title and noted down objectives  
- Assigned to read a review paper and methodology for the project  

### 🎯 Project Work
- Finalized project title  
- Wrote basic objectives  
- Discussed suitable ML models for project  

---

## 📅 Daily Diary - Day 12
**Date :** 10 july 2025

### ✅ Topics Covered
- Overfitting and Underfitting in ML  
- Project Preparation Tasks (Review Paper, Dataset Search, Role Distribution)  

### 📘 Key Learnings
- Overfitting happens when the model performs well on training data but poorly on unseen data  
- Underfitting occurs when the model fails to capture the underlying trend in data  
- Cross Validation is a technique used to evaluate and improve model performance  
- It helps reduce both overfitting and underfitting by training and testing the model on different data splits  

### 🔧 Tools / Platforms Used
- Online Research Platforms  
- Search Engines  

### 🧪 Tasks Performed
- Searched and read about Cross Validation  
- Understood how Cross Validation helps handle overfitting and underfitting  
- Task: How to remove overfitting and underfitting using cross validation  
- Searched for the latest review paper related to the project  
- Explored datasets relevant to the project  
- Divided roles among team members  

### 🎯 Project Work
- Shortlisted review paper  
- Looked into suitable datasets  
- Assigned specific roles to each member  

---

## 📅 Daily Diary - Day 13
**Date:** 11 july 2025

### ✅ Topics Covered
- Project Progress Review and Team Coordination  

### 📘 Key Learnings
- Regular project updates help track progress and manage deadlines  
- Team coordination is important to ensure timely completion of tasks  
- Clear role distribution improves efficiency in project development  

### 🔧 Tools / Platforms Used
- Blynk (for project interface planning)  

### 🧪 Tasks Performed
- Discussed progress made in the project so far  
- Shared updates on tasks like review paper, dataset search, and model selection  
- Explored Blynk app for project implementation  
- Ensured all team members are clear with their assigned roles  

### 🎯 Project Work
- Reviewed progress of each task  
- Identified pending tasks and assigned responsibilities  
- Continued working on project research and planning

---

## 📅 Daily Diary - Day 12
**Date:** 14 July 2025

### ✅ Topics Covered
- Introduction to project development phase  
- Team discussion on project scope and requirements  

### 📘 Key Learnings
- Importance of project planning before starting coding  
- Team coordination improves efficiency  
- Role distribution helps in tracking work  

### 🔧 Tools / Platforms Used
- Initial planning through discussion and brainstorming  

### 🧪 Tasks Performed
- Discussed objectives of the project  
- Identified required modules and components  
- Assigned roles to team members  

### 🎯 Project Work
- Finalized scope of the project  
- Planned next steps for coding and implementation  


## 📅 Daily Diary - Day 13
**Date:** 15 July 2025

### ✅ Topics Covered
- Project Progress Review and Team Coordination  

### 📘 Key Learnings
- Regular updates help track progress  
- Team coordination is important for deadlines  
- Role distribution ensures efficiency  

### 🔧 Tools / Platforms Used
- Blynk (for interface planning)  

### 🧪 Tasks Performed
- Shared updates on work completed  
- Discussed dataset search and model selection  
- Explored Blynk app for project interface  
- Ensured role clarity among team members  

### 🎯 Project Work
- Reviewed progress  
- Identified pending tasks  
- Continued research and planning  


## 📅 Daily Diary - Day 14
**Date:** 16 July 2025

### ✅ Topics Covered
- Dedicated time for project building  

### 📘 Key Learnings
- Practical implementation requires time and patience  
- Testing each module separately helps in integration later  

### 🔧 Tools / Platforms Used
- Project hardware (ESP32, sensors, etc.)  
- Software planning tools  

### 🧪 Tasks Performed
- Worked on assembling components of project  
- Divided tasks for coding and documentation  
- Discussed strategy for upcoming verification  

### 🎯 Project Work
- Initial project assembly started  
- Planned coding phase for next sessions  


## 📅 Daily Diary - Day 15
**Date:** 17 July 2025

### ✅ Topics Covered
- Project development continuation  

### 📘 Key Learnings
- Debugging is essential during project build  
- Importance of teamwork in troubleshooting  

### 🔧 Tools / Platforms Used
- Hardware kits (sensors, ESP32, breadboard)  
- Software tools for testing connections  

### 🧪 Tasks Performed
- Connected modules on breadboard  
- Checked wiring and connections  
- Planned next steps for coding implementation  

### 🎯 Project Work
- Hardware setup tested  
- Coding part planned for integration  


## 📅 Daily Diary - Day 16
**Date:** 18 July 2025

### ✅ Topics Covered
- Project verification preparation  

### 📘 Key Learnings
- Proper documentation is important for project submission  
- Continuous testing reduces errors later  

### 🔧 Tools / Platforms Used
- Project hardware (sensors, ESP32)  
- Software platform for testing  

### 🧪 Tasks Performed
- Continued project building  
- Prepared notes for documentation  
- Divided work for coding and testing  

### 🎯 Project Work
- Hardware progress continued  
- Documentation work started  

---

## 🎓 Training Certificate

I have successfully completed my 4-week training program.  

You can view my certificate by clicking the link below:

[📄 Click here to open my Training Certificate](./Training_Certificate(1).pdf)

