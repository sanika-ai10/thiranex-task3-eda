# Thiranex Task 3 — Exploratory Data Analysis

## Overview

This project was completed as part of the Thiranex Data Science Internship.

The objective of this project is to perform exploratory data analysis on a roller coaster dataset to uncover patterns, trends, and relationships between different features.

The analysis includes statistical summaries, data visualization, correlation analysis, feature exploration, and question-based analysis to understand the characteristics of roller coasters in the dataset.

## Dataset

The analysis uses a roller coaster dataset containing information about roller coasters from different years, manufacturers, locations, types, speeds, heights, inversions, G-force, and other characteristics.

- **Rows:** 1,087
- **Columns:** 56
- **Dataset file:** `coaster_db.csv`

The dataset was obtained from the Roller Coaster Database used in the EDA tutorial provided by Thiranex.

## Tools & Libraries

The project was developed using Python and the following libraries:

- **Pandas** — data loading, cleaning, manipulation, and statistical analysis
- **NumPy** — numerical operations
- **Matplotlib** — data visualization
- **Seaborn** — statistical visualizations and charts
- **Jupyter Notebook** — interactive development and analysis

## EDA Process

The exploratory data analysis was performed in the following stages:

1. **Data Understanding**
   - Loaded the dataset using Pandas.
   - Examined the first few rows.
   - Checked the dataset dimensions and column names.
   - Inspected data types and missing values using `df.info()`.
   - Generated statistical summaries using `df.describe()`.

2. **Feature Understanding**
   - Analyzed the distribution of roller coasters by year introduced.
   - Compared the number of steel, wooden, and other roller coasters.
   - Examined the distribution of roller coaster speeds.
   - Examined the distribution of roller coaster heights.
   - Identified the most represented manufacturers.

3. **Feature Relationships**
   - Investigated the relationship between coaster height and speed.
   - Calculated the correlation between height and speed.
   - Examined relationships between inversions and G-force.
   - Compared average speed across coaster types.
   - Used a correlation heatmap to examine relationships between numerical features.

4. **Question-Based Analysis**
   - Identified the fastest roller coasters in the dataset.
   - Examined their coaster types and manufacturers.
   
## Key Findings

- The dataset contains **1,087 roller coasters** across **56 columns**.
- **Steel** coasters are the most common type in the dataset, with 816 entries, followed by Wood with 198 and Other with 73.
- Height and speed show a relatively strong positive correlation of approximately **0.70**.
- Inversions and G-force show a moderate positive correlation of approximately **0.35**.
- The three most represented manufacturers are **Vekoma (135)**, **Bolliger & Mabillard (119)**, and **Intamin (99)**.
- The fastest coaster in the dataset is **Formula Rossa**, with a recorded speed of **149.1 mph**.
- The top 10 fastest coasters identified in the analysis are all classified as **Steel** coasters.
- **Intamin** appears multiple times among the fastest coasters in the dataset.

## Project Structure
```text
thiranex-task3-eda/
│
├── Thiranex_Task3_Exploratory_Data_Analysis.ipynb
├── coaster_db.csv
└── README.md
## How to Run

### 1. Clone the repository

```bash
git clone https://github.com/sanika-ai10/thiranex-task3-eda.git
cd thiranex-task3-eda

## Conclusion

This exploratory data analysis provided an overview of the characteristics and relationships present in the roller coaster dataset. Statistical summaries and visualizations helped identify patterns in coaster types, speeds, heights, manufacturers, inversions, and G-force.

The analysis also demonstrated how exploratory data analysis can be used to generate meaningful questions from a dataset and investigate relationships between different features.