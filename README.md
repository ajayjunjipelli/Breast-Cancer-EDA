# Breast Cancer Exploratory Data Analysis (EDA)

This repository contains an Exploratory Data Analysis (EDA) project on the **Breast Cancer Dataset**. The dataset provides various attributes of breast tumors to help predict whether they are **malignant (M)** or **benign (B)**.

## 📌 Project Overview

The goal of this analysis is to:
- Understand the distribution of tumor attributes.
- Identify key features that influence malignancy.
- Visualize patterns and relationships between variables.
- Prepare the data for further machine learning modeling.

## 📂 Dataset Information

- **Source**: [Breast Cancer Dataset]
- **Rows**: 569
- **Columns**: 32
- **Target Variable**: `diagnosis` (M = Malignant, B = Benign)

## 🔍 EDA Steps

1. **Data Collection**
   - Imported dataset using `pandas`
   - Checked for missing values and duplicates

2. **Data Cleaning**
   - Verified data types and statistics
   - Removed unnecessary columns (if any)

3. **Data Visualization**
   - **Countplot**: Showed distribution of `diagnosis`
   - **Histograms**: Displayed distribution of numerical features
   - **Boxplots**: Compared key features against diagnosis
   - **Scatter Plots**: Highlighted relationships between attributes
   - **Pie Chart**: Showed proportions of benign vs. malignant cases

4. **Key Findings**
   - Malignant tumors generally have larger **radius, perimeter, and area**.
   - There is a noticeable separation between benign and malignant tumors in key features.
   - The dataset is balanced enough for further analysis.

## 🛠️ Tools & Libraries

- **Python**
- **Pandas**
- **Seaborn**
- **Matplotlib**

## 🚀 Next Steps

- Feature Engineering
- Train Machine Learning Models
- Evaluate and Fine-Tune Performance

This project is for educational purposes only.

--
