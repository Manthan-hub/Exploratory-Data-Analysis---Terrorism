# Exploratory Data Analysis — Global Terrorism (GTD)

Exploratory analysis of the **Global Terrorism Database (GTD)** to understand how terrorist incidents vary across **time, geography, attack types, targets, and outcomes**. The project focuses on turning a large, messy real-world dataset into **clear insights and visuals** that can support high-level reporting and further modeling.

---

## Dataset

**Source (Kaggle):** Global Terrorism Database (GTD) by START Consortium  
- Link: https://www.kaggle.com/datasets/START-UMD/gtd  
- File used in this project: `globalterrorismdb_0718dist.csv`  
- Coverage: **1970–2017** (with known missingness caveats typical to GTD releases)

> Note: This repository does **not** commit the full dataset file to GitHub (it is large). Follow the steps below to download it locally.

---

## Project Goals

This EDA answers questions like:

1. How have incident counts changed **year-by-year**?
2. Which **regions/countries/cities** are most affected?
3. What are the most common **attack types**, **target types**, and **weapon types**?
4. How do **fatalities and injuries** vary by geography and attack patterns?
5. What are the **highest-severity** periods/regions (not only highest count)?

---

## Key Highlights (from the notebook)

- The dataset is large-scale and wide: **~181k incidents and 100+ columns**, which makes **data cleaning + missing-value handling** a major part of analysis.
- Year-wise incident trends show clear peaks in specific recent years (as visualized in the notebook).
- Certain target categories (e.g., private citizens/property in GTD taxonomy) appear frequently in the analysis outputs.
- Country/region breakdowns identify concentrated hotspots rather than uniform global distribution.

> Replace these bullets with the exact numbers from your final charts once you lock the final analysis.


## How to Run Locally

### 1) Download the dataset
1. Go to the Kaggle dataset page: https://www.kaggle.com/datasets/START-UMD/gtd  
2. Download the dataset and locate: `globalterrorismdb_0718dist.csv`

### 2) Place it in your project folder
Create a folder named `data/` and place the CSV inside:
- `data/globalterrorismdb_0718dist.csv`

### 3) Install dependencies
```bash
pip install -r requirements.txt
