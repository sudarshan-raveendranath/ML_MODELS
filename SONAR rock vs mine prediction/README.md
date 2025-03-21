# 🚀 Sonar Rock vs Mine Classification using Logistic Regression

![Python](https://img.shields.io/badge/Python-3.8%2B-blue.svg)
![Machine Learning](https://img.shields.io/badge/Machine%20Learning-Logistic%20Regression-green.svg)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen.svg)

## 📌 Overview
This project implements a **Logistic Regression** model to classify sonar signals as either **rocks** or **mines** using **machine learning**. The dataset consists of **numerical sonar frequency readings** to determine whether the detected object is a rock or a mine.

---

## 📂 Table of Contents
- [📌 Overview](#-overview)
- [📊 Dataset](#-dataset)
- [⚙️ Installation](#%EF%B8%8F-installation)
---

## 📊 Dataset
- The dataset used is **`sonar_data.csv`**, which contains **numerical feature values** representing sonar signal strength at different frequencies.
- The last column (**column 60**) is the **target label**:
  - **`R`** → Represents **Rock**.
  - **`M`** → Represents **Mine**.

---

## ⚙️ Installation
Ensure the following libraries are installed before running the project:

```sh
pip install numpy pandas matplotlib seaborn scikit-learn
