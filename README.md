# Electric Bike Rental

## 🔹 Data Analyst – Electric Bike Rental Usage

### 📋 Project Overview

This project presents a comprehensive analysis of usage data from an electric bike rental service. The goal was to uncover insights into customer behavior, operational efficiency, and ticket usage patterns using real-world ride data. The dataset includes over 1,600 trips and captures attributes such as cost, distance, duration, energy consumed, and station activity.

### 🎯 Objectives

* Clean and preprocess raw trip data for analysis.
* Explore ride patterns based on ticket type, duration, and location.
* Identify operational inefficiencies (e.g., bike surplus/deficit by station).
* Conduct statistical testing to validate hypotheses around energy use, ride duration, and ticket type.

### 🛠️ Tools & Technologies

* **Python**
* **Pandas**, **NumPy**
* **Matplotlib**, **Seaborn**
* **SciPy**, **Statsmodels**
* **Jupyter Notebook**

### 🧠 Key Highlights

* Cleaned and transformed raw trip data, handling outliers and missing values.
* Created visualizations showing ride frequency by station, month, and ticket type.
* Engineered new metrics like `net_energy_gain` and `electricity_consumption_rate`.
* Applied statistical tests (Mann-Whitney U, Spearman, Chi-square) to validate behavioral and operational hypotheses.
* Proposed station-level bike redistribution strategies based on usage patterns.

### 📊 Insights

* Most trips used "single" tickets, especially in summer months.
* Station "TORI" had the highest traffic; "SATAMA" showed the largest bike deficit.
* On average, energy usage exceeded energy collected, highlighting battery inefficiencies.
* Trip durations slightly longer for "single" ticket holders vs "season" pass users.

---
