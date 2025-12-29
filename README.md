# 🌍 Remote Work Affordability Index

**Data Management Project**

## 📌 Project Overview

This project analyzes and ranks **significant European cities** based on their suitability for **remote workers and digital nomads**.
The analysis combines multiple real-world datasets (cost of living, traffic, pollution, safety, health care, and workation factors) to compute meaningful indices such as:

* City Attractiveness Index
* City Affordability Index
* City Quality of Life Index

The final output helps users compare cities using data-driven insights.

---

## 📂 Project Structure

The repository contains **Jupyter Notebook files (`.ipynb`)** and **one source CSV file**:

* **Workation data**

  * `best_cities_for_a_workation.csv`
  * `best_significant_european_workation_cities.ipynb`

* **Cost of Living**

  * `significant_european_cities_cost_of_living.ipynb`

* **Traffic**

  * `significant_european_cities_traffic_index.ipynb`

* **Pollution**

  * `significant_european_cities_pollution_index.ipynb`

* **Health Care**

  * `significant_european_cities_health_care_index.ipynb`

* **Crime & Safety**

  * `significant_european_cities_crime_safety_index.ipynb`

* **Final Analysis & Visualization**

  * `significant_european_cities_analysis_and_visualization.ipynb`
  * `significant_european_cities_quality_of_life_index.ipynb`

---

## 🧠 Key Features

* Data cleaning and normalization
* Handling spelling inconsistencies across datasets
* Merging multiple datasets into a unified structure
* Index calculation using weighted formulas
* Visualizations for:

  * Top 10 cities by affordability
  * Top 10 cities by attractiveness
  * Top 10 cities by quality of life

---

## ▶️ How to Use This Project

### 1️⃣ Requirements

You can run all files using:

* **Jupyter Notebook**
* **JupyterLab**
* **VS Code (with Python extension)**

Make sure you have:

```bash
python >= 3.8
pandas
numpy
matplotlib
```

---

### 2️⃣ Open the Notebooks

All `.ipynb` files can be opened directly in Jupyter Notebook.

Start Jupyter:

```bash
jupyter notebook
```

---

### 3️⃣ Update File Paths (Important ⚠️)

This project uses **local file paths**.

👉 When running the notebooks:

* Update file paths in each notebook to match your local directory structure.
* Example:

```python
pd.read_csv("path/to/best_cities_for_a_workation.csv")
```

This is required for the notebooks to run correctly on your system.

---

### 4️⃣ Execution Order (Recommended)

1. Workation dataset notebook
2. Cost of Living notebook
3. Traffic notebook
4. Pollution notebook
5. Health Care notebook
6. Crime & Safety notebook
7. Final merge, analysis, and visualization notebook

---

## 📊 Output

* Cleaned and merged datasets
* Computed indices for each city
* Ranking of top 10 cities
* Visual charts for easy interpretation

---

## 👥 Team Contribution

* **Arianna Serena** – Research questions, index formulation, data enrichment
* **Giulia Cristea** – Dataset merging, visualization, technical documentation
* **Osama Haider** – Data integration logic, data consistency, MongoDB migration

---

## 📎 Notes

* All datasets were cleaned before analysis
* Spelling inconsistencies across sources were handled programmatically
* The project is designed for **academic and analytical use**
