🌍 Climate Change Trend Analysis Using Python

📌 Project Overview

This project analyzes global climate change by studying the relationship between **temperature increase** and **CO₂ emissions** over time using Python.

The goal is to understand:

* Is global temperature increasing?
* Are CO₂ emissions increasing?
* Is there a relationship between the two?
🎯 Objectives

* Analyze global temperature trends using historical data
* Analyze global CO₂ emissions trends
* Compare both datasets to identify relationships
* Visualize climate change patterns using graphs


 📊 Datasets Used

 🌡️ Temperature Data

* Source: NASA GISTEMP
* Description: Global land-ocean temperature anomalies (1880–present)

🌫️ CO₂ Data

* Source: Our World in Data
* Description: CO₂ emissions per capita (global data used)

---

## 🧰 Tools & Technologies

* Python
* Pandas
* Matplotlib
* Jupyter Notebook

---

## ⚙️ Methodology

### 1. Data Collection

* Downloaded datasets in CSV format
* Used global (“World”) data for consistency

### 2. Data Cleaning

* Removed unnecessary columns
* Handled missing values
* Converted data to numeric format

### 3. Data Processing

* Applied 5-year rolling average to smooth temperature data
* Grouped CO₂ data by year

### 4. Data Visualization

* Temperature trend graph
* CO₂ emissions trend graph
* Combined comparison graph

5. Data Analysis

* Merged datasets using Year
* Compared trends visually
* Observed relationship between variables

---

📈 Results & Findings

* Global temperature shows a clear increasing trend
* CO₂ emissions have increased significantly over time
* Both variables show similar upward patterns
* This indicates a strong relationship between CO₂ emissions and global warming

---

📊 Sample Visualizations

<img width="1189" height="590" alt="image" src="https://github.com/user-attachments/assets/877f1932-07e1-415e-82c6-ad335f4a0de3" />


🧠 Conclusion

The analysis confirms that:

* Global warming is evident from temperature data
* CO₂ emissions are a major contributing factor
* There is a strong correlation between rising CO₂ levels and temperature increase

📂 Project Structure

```
climate-change-analysis/
│
├── data/
├── notebooks/
├── images/
├── src/
├── README.md
└── requirements.txt
📚 References

* NASA GISTEMP Dataset
* Our World in Data (CO₂ emissions)
