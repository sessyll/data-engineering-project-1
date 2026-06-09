# 📊 CBS Open-Data Engineering & Visualization Pipeline

[![License: MIT](https://shields.io)](https://opensource.org)
[![Python](https://shields.io)](https://python.org)
[![Bit Academy](https://shields.io)](https://bit-academy.nl)
[![Framework](https://shields.io)](https://pydata.org)

## 📌 Project Overview
This repository contains the official final graduation assignment (**eindopdracht**) completed for the **Junior Data Engineering Certification Program** at **Bit Academy**. 

The core architecture of this project is a programmatic ETL (Extract, Transform, Load) pipeline that establishes a live connection with the **Central Bureau for Statistics (CBS)** in the Netherlands. It bypasses the need for local static files by programmatically ingesting, parsing, and cleaning socio-economic data points, followed by exploratory data analysis (EDA) and advanced statistical visualizations.

---

## 🎹 Professional Context & Background
As a **classical pianist (MMus)** with a deep-rooted interest in analytical research, I built this end-to-end data pipeline to bridge the gap between complex statistical databases and domain-specific insights. 

Mastering these modern data engineering processes allows me to transition raw, multi-dimensional public datasets into scalable, reproducible data-driven charts. This foundation is explicitly designed to elevate the empirical quality of professional research, cross-disciplinary publications, and high-level presentations.

---

## 🛠️ System Architecture & Tech Stack

The workspace relies on a lightweight, modular infrastructure optimized for data analytics:

*   **Data Sourcing & Ingestion:** `cbsodata` (Official Python API Wrapper for Netherlands CBS StatLine)
*   **Data Manipulation & ETL:** `pandas` & internal `csv` parsers for vectorization, column filtering, and handling missing data values.
*   **Data Visualization Studio:** `seaborn` and `matplotlib.pyplot` for rendering multi-variable distributions, trend matrices, and demographic correlations.
*   **Algorithmic Utilities:** Built-in `random` engines for randomized sampling checks.

---

## 🚀 Key Engineering Features

1.  **Dynamic Data Stream:** Eliminates outdated local CSV files by calling the live CBS open-data REST infrastructure on every runtime execution.
2.  **Clean Data Transformations:** Converts raw API dictionary matrices into highly queryable Pandas DataFrames with proper data type formatting.
3.  **Advanced Statistical Charting:** Employs Seaborn's advanced statistical algorithms to output granular plots, making data storytelling immediate and clear.
4.  **Reproducible Workspace:** Fully integrated with VS Code and standard Python virtual environments for instant setup.

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
Open your `.ipynb` work file inside VS Code and select **"Run All"** from the top controls. The script will ping the CBS servers, stream the core data tables, and generate the graphics stack immediately.

---

## 📄 License
This architecture is open-source software licensed under the terms of the [MIT License](LICENSE).
