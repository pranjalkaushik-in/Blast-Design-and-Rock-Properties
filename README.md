# ⛏️ Blast Design & Rock Stiffness Analysis for Fragmentation

## 📌 Project Overview

This project investigates how **blast design parameters, powder factor, and rock stiffness interact to influence rock fragmentation** across different mines and rock formations.

The analysis uses data compiled from a published blasting research study covering **110 blast observations from 10 mines and quarries across 5 countries**. The dataset contains **97 model-development blasts and 13 independent validation blasts**.

For the main analysis and Power BI dashboard, **97 model-development blasts** were used.

The project combines **Mining Engineering concepts with Python, Pandas, and Power BI** to identify relationships between blast design and fragmentation performance.

---

## 🎯 Research Question

> **How do blast design ratios (burden-spacing-stemming-bench height) and powder factor interact with rock stiffness to determine fragmentation outcomes across different mine types and rock formations worldwide?**

The analysis focuses on understanding whether fragmentation is controlled by a single blast parameter or by the interaction between **blast design and rock mass characteristics**.

---

## 🔍 Project Objectives

- Analyze the relationship between **powder factor and mean fragment size**.
- Investigate the influence of **blast design ratios** on fragmentation.
- Compare fragmentation between **high- and low-stiffness rock groups**.
- Examine the role of **in-situ block size** in fragmentation outcomes.
- Compare fragmentation across different **mines, rock types, and mine types**.
- Identify blast-design conditions associated with finer fragmentation.
- Develop an interactive dashboard for communicating the engineering findings.

---

## 📊 Dataset

The dataset was compiled from published research on blast fragmentation.

### Dataset Coverage

| Description | Value |
|---|---:|
| Total blast observations | 110 |
| Model-development blasts | 97 |
| Validation blasts | 13 |
| Mines & quarries | 10 |
| Countries | 5 |
| Mine types | 3 |
| Rock types | 8 |

### Main Variables

The dataset includes:

- Blast ID
- Mine name
- Country
- Rock type
- Mine type
- Spacing-to-burden ratio
- Bench-height-to-burden ratio
- Burden-to-hole-diameter ratio
- Stemming-to-burden ratio
- Powder factor
- In-situ block size
- Modulus of elasticity
- Mean fragment size

### Target Variable

**Mean Fragment Size (cm)**

Lower mean fragment size represents finer fragmentation.

---

## 🛠️ Tools & Technologies

- **Python**
- **Pandas**
- **Matplotlib**
- **Google Colab**
- **Microsoft Power BI**
- **DAX**

---

# 🔬 Methodology

The project was completed through the following workflow:

```text
Published Research Dataset
          ↓
Data Compilation & Cleaning
          ↓
Exploratory Data Analysis
          ↓
Rock Stiffness Group Comparison
          ↓
Powder Factor Analysis
          ↓
Correlation Analysis
          ↓
Mine & Rock Type Analysis
          ↓
Engineering Interpretation
          ↓
Power BI Dashboard
