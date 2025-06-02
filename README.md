# XAI-Unsupervised-Learning-Tutorial

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/imperonas/XAI-Unsupervised-Learning-Tutorial/HEAD?labpath=excercise.ipynb)

![Pandas](https://img.shields.io/badge/Pandas-library-green)
![NumPy](https://img.shields.io/badge/NumPy-library-blue)
![SciPy](https://img.shields.io/badge/SciPy-library-orange)
![Seaborn](https://img.shields.io/badge/Seaborn-library-lightblue)

---

This repository contains a series of excecises within a Jupyter notebook designed to teach key concepts in eXplainable AI (XAI) for unsupervised learning. The tasks focus on manually inspecting data, calculating entropy, and understanding feature importance through local and global FIS (Feature Information Score) metrics.

## **Exercises Overview**

### **1. Load and Inspect the Dataset**
- Load a dataset (`mocked_dataset.csv`) into a Pandas DataFrame using `pd.read_csv`.
- Inspect the dataset to understand its structure and contents.

### **2. Calculate Shannon Entropy**
- Manually calculate Shannon entropy using:
  - NumPy's `log2` and `sum` functions.
  - The `scipy.stats.entropy` function.

### **3. Implement the Local FIS Calculation**
- Implement a function to calculate the **local FIS** score for a specific feature 

### **4. Use the Local FIS Function**
- Compute local FIS values for three features (**Group**, **Type**, **Subgroup**) in a given cluster.
- Output the results as a `pd.DataFrame` with columns: **Feature**, **lFIS**, and **Cluster**.

### **5. Calculate the Global FIS Score**
- Implement a function to calculate the **global FIS score** for all features across all clusters.

## **Getting Started**

### **Requirements**
- Python 3.x
- Required Python packages from `requirements.txt`  as well as any requirements for jupyter servers
  
### **Setup**
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/explainable-ai-unsupervised-learning.git
   cd explainable-ai-unsupervised-learning
   ```
2. Install the dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Open the Jupyter notebook to start the exercises:

- `README.md`: This file.

## **License**
This project is licensed under the MIT License.
