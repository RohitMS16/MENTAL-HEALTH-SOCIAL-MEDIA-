# Mental Health & Social Media – Exploratory Data Analysis (EDA)

## 📌 Project Overview

This project performs **Exploratory Data Analysis (EDA)** on a *Mental Health & Social Media* dataset. The goal is to understand data distributions, identify unusual patterns, and handle outliers while preserving real-world behavioral information.

The analysis focuses on numerical features such as age, screen time, social media usage, sleep hours, and mental health indicators.

---

## 🎯 Objectives

* Understand the structure and distribution of the dataset
* Visualize numerical features using boxplots and histograms
* Detect outliers using the **Interquartile Range (IQR)** method
* Treat outliers using **IQR-based capping** instead of deleting rows
* Prepare clean data suitable for further analysis or machine learning

---

## 🛠️ Tools & Technologies

* **Python**
* **Pandas** – data manipulation
* **Matplotlib** – data visualization
* **Jupyter Notebook**

---

## 🔍 Key Steps Performed

1. Loaded and inspected the dataset
2. Identified numerical columns
3. Visualized distributions using boxplots
4. Detected outliers using the IQR method
5. Treated outliers by capping extreme values (no extra columns created)
6. Re-visualized data to verify cleaning

---

## 📊 Outlier Handling Approach

* Outliers were identified using:
  [Q1 - 1.5 × IQR,; Q3 + 1.5 × IQR]
* Instead of removing data points, **capping (winsorization)** was applied
* This approach preserves dataset size and real-world variability

---

## ✅ Results

* Extreme outliers were successfully reduced
* Original columns were preserved
* Dataset remains realistic and ML-ready

---

## 📁 Repository Structure

```
├── Project2.ipynb   # Jupyter Notebook containing EDA and outlier treatment
├── README.md        # Project documentation
```

---

## 🧠 Conclusion

Outliers in human behavioral data are often meaningful. By using IQR-based capping, this project ensures that rare but valid observations are retained while reducing their impact on analysis.

---

## 📬 Contact

**Rohit MS**
BCA Graduate | Data Science Enthusiast
[LinkedIn](https://www.linkedin.com/in/rohit-ms-96b015292)
