# 📊 CBS Open-Data Engineering & Visualization Pipeline

[![License: MIT](https://shields.io)](https://opensource.org)
[![Python](https://shields.io)](https://python.org)
[![Bit Academy](https://shields.io)](https://bit-academy.nl)
[![Framework](https://shields.io)](https://pydata.org)

## 📌 Project Overview
This repository contains the official final graduation assignment (**eindopdracht**) completed for the **Junior Data Engineering Certification Program** at **Bit Academy**. Project Metadata: Developed in June 2022 as part of the graduation program. Uploaded to GitHub in 2026 for portfolio curation.

The project retrieves performing-arts data from CBS StatLine through the `cbsodata` Python package. The retrieved records are converted into a pandas DataFrame, after which selected columns are renamed, filtered, aggregated and visualized.

---

## 🎹 Professional Context & Background
As a **classical pianist (MMus)** with a deep-rooted interest in analytical research, I built this end-to-end data pipeline to bridge the gap between complex statistical databases and domain-specific insights. 

This project allowed me to practise retrieving public data programmatically and using pandas, Matplotlib and Seaborn to explore and communicate the results.

---

## 🛠️ Tools and Techniques

The workspace relies on a lightweight, modular infrastructure optimized for data analytics:

- **Data retrieval:** `cbsodata` for retrieving CBS StatLine data.
- **Data preparation:** `pandas` for converting the retrieved records into a DataFrame, renaming columns, removing duplicate IDs, filtering rows and selecting relevant columns.
- **Calculations:** `pandas` operations such as `groupby`, `sum`, `mean` and percentage calculations.
- **Data visualization:** `seaborn` and `matplotlib.pyplot` for creating line, scatter, pie, box and bar charts.

---

## 🚀 Main Features

1. **API-based data retrieval:** Retrieves CBS table `70077NED` through the `cbsodata` package whenever the notebook is run.
2. **Data preparation:** Renames and selects relevant columns, removes duplicate IDs and filters national and regional categories.
3. **Aggregation and calculations:** Uses sums, averages and percentages to compare performances and visitor figures.
4. **Exploratory visualization:** Presents the results through several chart types created with Matplotlib and Seaborn.

---

## 📦 Getting Started & Local Installation

To spin up this Jupyter Notebook workspace on your local machine, follow these technical steps:

### 1. Environment Setup
Clone this repository to your target directory:
```bash
git clone https://github.com
cd data-engineering-project-1
```

### 2. Dependency Management
Open the workspace in **Visual Studio Code** and select your active Python kernel. Execute the deployment script in your notebook or run the following command in your terminal to host the required packages:
```bash
pip install jupyter cbsodata pandas matplotlib seaborn
```

### 3. Execution
Open your `.ipynb` work file inside VS Code and select **"Run All"** from the top controls. The notebook will retrieve the CBS table and generate the analyses and visualizations when the cells are run in order.

---

## 📄 License
This architecture is open-source software licensed under the terms of the [MIT License](LICENSE).
