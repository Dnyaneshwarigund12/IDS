# 🔐 Intrusion Detection System (IDS) using Machine Learning

An Intrusion Detection System (IDS) built using machine learning algorithms to detect various types of network intrusions including DoS, Probe, and other attack types, based on the KDD dataset structure.

---

## 📌 Table of Contents

- [About the Project](#about-the-project)
- [Dataset](#dataset)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Project Workflow](#project-workflow)
- [Results](#results)
- [Future Improvements](#future-improvements)
- [License](#license)

---

## 📖 About the Project

This project implements an ML-based Intrusion Detection System capable of classifying network traffic as normal or malicious. It leverages various supervised machine learning algorithms and compares their performance to find the most effective model.

---

## 🗂 Dataset

- The dataset is derived from the **KDD Cup 99** dataset.
- Each record represents a network connection.
- Contains both categorical and numerical features.
- Target labels include:
  - Normal
  - DoS (Denial of Service)
  - Probe
  - R2L (Remote to Local)
  - U2R (User to Root)

---

## 🛠 Technologies Used

- **Python**
- **Jupyter Notebook**
- **Pandas, NumPy** – Data handling
- **Scikit-learn** – Machine learning models and preprocessing
- **Matplotlib, Seaborn** – Visualization
- **LabelEncoder, MinMaxScaler** – Data preprocessing tools

---
