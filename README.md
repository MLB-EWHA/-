# MLB_EWHA Machine Learning Project

This repository contains the implementation of the **Machine Learning** course project. The project explores **Closed-world** and **Open-world** classification tasks using datasets of monitored and unmonitored websites.

---

## 📂 Repository Structure

- **`Datasets/`**: Contains the processed datasets:
  - `mon.csv`: Features extracted from the `mon_standard.pkl` file.
  - `unmon.csv`: Features extracted from the `unmon_standard10.pkl` file.

- **`Task Process/`**: Includes all the code used during project development.

- **`Optimized Models/`**: Contains optimized code for evaluation purposes.

- **`load_pickle_code.ipynb`**: Sample code for feature extraction and conversion of `.pkl` files to arrays.

---

## 📊 Project Overview

### 1️⃣ Closed-World Classification
- **Objective**: Classify 95 monitored websites into 95 unique labels.
- **Dataset**: `mon.csv` (processed from `mon_standard.pkl`).

### 2️⃣ Open-World Classification
- **Objective**: Include both monitored and unmonitored datasets for the following tasks:
  - **Binary Classification**: Predict whether a trace is monitored (`1`) or unmonitored (`-1`).
  - **Multi-Class Classification**: Classify 95 monitored websites (`0-94`) and unmonitored websites (`-1`) into a total of 96 classes.

---

## 📚 Datasets

### Download Links:
- **[mon_standard.pkl](https://drive.google.com/drive/folders/13sDplxKUNmntbYr6WhpqQARiBvH41Oum)**
- **[unmon_standard10.pkl](https://drive.google.com/drive/folders/13sDplxKUNmntbYr6WhpqQARiBvH41Oum)**

### Dataset Details:

| Dataset               | Instances | Classes               | Description                                                                                      |
|-----------------------|-----------|-----------------------|--------------------------------------------------------------------------------------------------|
| `mon_standard.pkl`    | 19,000    | 95                    | Monitored website traces. Each website has 10 subpages, observed 20 times each.                 |
| `unmon_standard10.pkl`| 3,000     | - (unmonitored only)  | Unmonitored website traces.                                                                     |

---

## 🚀 Setup and Execution

### 1️⃣ Environment

The code was executed in the following environment:
- **Python Version**: 3.8.10

### 2️⃣ Required Libraries

To run the code, the following Python libraries need to be installed:
- pandas
- numpy
- matplotlib
- scikit-learn
- xgboost
- imbalanced-learn
  
```bash
pip install pandas numpy matplotlib scikit-learn xgboost imbalanced-learn
```

### 3️⃣ Steps to Run

1. Clone the repository and navigate to the project directory.

2. Install the required libraries listed above.

3. Run the desired classification tasks:
   - Closed-World Classification
   - Open-World Binary Classification
   - Open-World Multi-Class Classification

---

## 👨‍💻 Team

**Team Name**: MLB_EWHA

- Team Members:
  - Yoon juyoung
  - Member 2
  - Member 3
  - Member 4
  - Member 5

For any questions or clarifications, please contact us via email
