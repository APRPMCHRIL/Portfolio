# Portfolio
<h1 align="center">Hi there! 👋 I'm Arparat Pummuang</h1>

<p align="center">
  💻 Junior Pentester | 🤖 Machine Learning Enthusiast | 🌐 Full-Stack Developer  
</p>

---

## 🧑‍💻 About Me

I'm an enthusiastic and detail-oriented Computer Engineering student with a strong foundation in **Cybersecurity**, including **penetration testing** of web/mobile applications, APIs, and network infrastructure. I also have experience in **Machine Learning**, particularly in **classification tasks**, and have applied **Natural Language Processing (NLP)** techniques in research projects.

Additionally, I have experience building **full-stack web applications** using **React** and **TypeScript** on the frontend, and **Golang** for backend development. I’ve worked on projects following a **Scrum-based workflow**, and enjoy working collaboratively using tools like Git.

---

## 🛠️ Skills & Tools

**Languages:**  
Python · Java · C · Golang · TypeScript · PHP · CSS · HTML(still learning) · JavaScript(still learning)

**Tools & Frameworks:**  
React · Arduino · MySQL · Orange Data Mining · Burp Suite · Cisco Packet Tracer · VS Code · figma · 
tensorflow · pytorch · pandas · numpy · transformers · sklearn.metrics · seaborn 

**Other Skills:**  
Linux · Git · Critical Thinking · Communication · MySQL

---

## 📂 Featured Projects

| Project | Description | Tech |
|--------|-------------|------|
| [🔐 Sensitive Code Detection](#) | Detects risky code patterns using machine learning to support cybersecurity | Python, NLP, ML |
| [📧 Spam Email Detection](#) | ML model to classify emails as spam or not using Orange Data Mining and classification models | Python, Orange3 |
| [🎥 Movie Streaming Platform](#) | Playlist and download system for a movie streaming web app | React, TypeScript, Golang |

---

## 🎓 Education

**Suranaree University of Technology**  
B.Eng. in Computer Engineering (2021–2025)  
- GPAX: 3.14  
---

## 📫 Contact Me

- 📧 Email: ar.pummuang@gmail.com  
- 🌐 Location: Bangkok, Thailand  
---

⭐️ explore my repositories and connect with me!

---

## 📧 Spam Email Detection (Group Research Project)

A machine learning classification project developed as part of a university research group. The goal was to build and evaluate models for classifying spam and non-spam emails using different algorithms.

**🧠 My Role:**  
- Preprocessed data from UCI and Enron datasets  
- Built ML pipelines using Orange Data Mining  
- Evaluated models (SVM, Naive Bayes, Neural Network, Random Forest)  
- Analyzed metrics such as AUC, F1-score, Recall and Precision

**🛠 Tech Used:**  
Python, Orange3, UCI Spambase Dataset, Enron Dataset

**📊 Result Highlights:**  
- Random Forest and Neural Network showed best performance (AUC ~0.98)
- SVM struggled with spam recall  
- Key takeaway: data preprocessing and model choice matter

---

## 🎥 Movie Streaming Web (Group Project)

A full-stack web application for watching and downloading movies, with playlist features.

**🧠 What I did:**  
- Built frontend UI using React and TypeScript  
- Developed backend API using Golang

**🛠 Tech Used:**  
React, TypeScript, Golang, REST API

---

## 🔐 Sensitive Code Detection: Enhancing Cybersecurity with Machine Learning

This project aims to detect **sensitive or risky source code** using **Machine Learning** and **Natural Language Processing (NLP)** techniques. It supports developers and security teams in identifying code snippets that could expose personal data, secrets, or vulnerabilities.

### 🎯 Objective

To build a machine learning model capable of classifying code snippets as **sensitive** or **non-sensitive**, and analyze their patterns for better code security and prevention of data breaches.

### 🧠 Key Features

- Binary classification of source code: Sensitive (1) vs Non-Sensitive (0)
- Applies NLP techniques to extract features from raw code
- Utilizes models like DeBERTa and CodeBERT
- Analyzes code based on entropy, keywords, and matched patterns
- Optional: Extracts metadata such as file path, line number, and type of risk (e.g., API key, hardcoded password)

**🛠️ Tools & Technologies**

- Python
- Scikit-learn
- Pandas, NumPy
- Jupyter Notebook
- (Optional): DeBERTa, HuggingFace Transformers

**📁 Dataset**

The dataset includes code samples labeled as:
- `1`: Sensitive (e.g., secrets, credentials, hardcoded keys)
- `0`: Non-sensitive

Source: Manually labeled + adapted from open repositories and simulated risky code.

*repo:* https://github.com/APRPMCHRIL/ML_DeBERTa_Classification_Sensitive_Code.git

---

## Fire Alarm System (Operating Systems Course)

**Technologies:** Raspberry Pi, DHT22 (Temperature & Humidity Sensor), Flame Sensor, Buzzer  
**Project Type:** Group project for the Operating Systems course  
**Responsibilities:**  
- Assembled and connected the DHT22, flame sensor, and buzzer with Raspberry Pi GPIO pins according to the designed circuit  
- Wrote Python code to read sensor values and control outputs  
- Practiced working with Linux-based GPIO and multitasking concepts (threads/processes)

**Key Features:**
- 🔊 Fire alert via buzzer sound when flame is detected
- 📲 Sends fire alert to LINE Application in real-time
- 🌡️ Monitors temperature and humidity continuously when the flame sensor detects fire
- 📝 Logs temperature and humidity data during fire alerts for record and analysis

---
