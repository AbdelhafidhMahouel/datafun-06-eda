# Project 6 – Custom Exploratory Data Analysis (EDA)

> Exploratory data analysis using modern Python tooling (`uv`, `pyproject.toml`) and Jupyter notebooks.

---

## Overview and Scope

This repository contains **Project 6** for a data analytics course.  
The purpose of this project is to perform **custom exploratory data analysis (EDA)** using a new dataset while following **modern Python project standards**.

This project focuses on:
- Exploring a real-world dataset
- Using visualizations and summary statistics to discover patterns
- Managing dependencies with **uv** and **pyproject.toml**
- Documenting the analysis clearly and professionally

---

## Dataset Description

**Dataset Name:** Titanic Dataset (Seaborn)

**Source:** Built-in Seaborn dataset  
https://seaborn.pydata.org/generated/seaborn.load_dataset.html

**Description:**  
The Titanic dataset contains information about passengers aboard the RMS Titanic, including survival status, passenger class, gender, age, and fare. The dataset is commonly used to explore relationships between demographic factors and survival outcomes.

**Key Columns:**
- `survived` – Survival status (0 = No, 1 = Yes)
- `pclass` – Passenger class
- `sex` – Gender
- `age` – Passenger age
- `fare` – Ticket fare
- `embarked` – Port of embarkation

---

## Repository Contents

- `mahouel_eda.ipynb` – Jupyter Notebook containing the EDA
- `pyproject.toml` – Project metadata and dependencies
- `.gitignore` – Ignored files and folders
- `README.md` – Project documentation

---

## Installation and Environment Setup (uv)

This project uses **uv** to manage the Python environment and dependencies.

### Clone the repository
```bash
git clone https://github.com/AbdelhafidhMahouel/datafun-06-eda
cd datafun-06-eda