
```markdown
# Pain Level Classification Using Machine Learning Algorithms

## Overview
This project classifies human pain levels (1-8) using physiological 
signals collected from wearable biosensors.
The dataset contains 96,000 records from 200 patients.
Six machine learning algorithms were implemented using both 
built-in scikit-learn library and from scratch using Python and NumPy.

---

## Dataset
- **Name:** Pain Dataset (200 Patients, 4Hz)
- **Records:** 96,000
- **Features:** 7
- **Target:** pain_scale (1-8)
- **Missing Values:** None

### Features
| Feature | Description |
|---|---|
| acc_x, acc_y, acc_z | Accelerometer - body movement |
| EDA | Electrodermal Activity - skin conductance |
| BVP | Blood Volume Pulse - blood flow |
| HR | Heart Rate - heartbeats per minute |
| temp | Skin Temperature |

---

## Algorithms Implemented
| Algorithm | Built-in | Scratch |
|---|---|---|
| Decision Tree 
| Random Forest | ✅ | ✅ |
| Linear Regression | ✅ | ✅ |
| Logistic Regression | ✅ | ✅ |
| KNN | ✅ | ✅ |
| Naive Bayes | ✅ | ✅ |

---

## Results

### Built-in vs Scratch
| Algorithm | Built-in | Scratch |
|---|---|---|
| Decision Tree | 72.86% | 42.20% |
| Random Forest | 87.41% | 55.35% |
| Linear Regression | 36.05% | 36.05% |
| Logistic Regression | 42.61% | 31.51% |
| KNN | 67.07% | 64.60% |
| Naive Bayes | 34.68% | 34.68% |

### Best Model
**Random Forest — 87.41%**

---

## Requirements
```
pip install numpy pandas scikit-learn matplotlib seaborn
```

## How to Run
1. Clone the repository
```
git clone https://github.com/Hasnaa-Nageh/Machine-Learning-Project
```
2. Open the notebook
```
jupyter notebook pain_classification.ipynb
```
3. Upload the dataset
```
pain_dataset_200P_4hz.csv
```
4. Run all cells

---

## Project Structure
```
├── pain_classification.ipynb  ← Main notebook
├── pain_dataset_200P_4hz.csv  ← Dataset
├── README.md                  ← This file
```

---

## Author
- **Name:** Hasnaa Nageh
- **Course:** Machine Learning
```
---
