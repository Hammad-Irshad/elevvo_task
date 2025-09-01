
# Task 3: Forest Cover Type Classification - Elevvo Internship

This project classifies forest cover types based on cartographic and environmental features using a multi-class machine learning model.

---

## 📁 Project Structure

```
task 3/
├── code.ipynb             # Main notebook
├── covtype.data.gz        # UCI dataset (compressed)
├── forest_model.pkl       # Trained Random Forest model
├── covtype.info           # Dataset description from UCI
└── README.md              # This file
```

---

## 📊 Dataset

**Source:** [UCI Covertype Dataset](https://archive.ics.uci.edu/dataset/31/covertype)

- 581,012 rows × 55 columns
- Features: Elevation, Slope, Soil_Type, Wilderness_Area, etc.
- Target: `Cover_Type` (classes 1–7 representing forest types)

---

## ⚙️ Tools Used

- Python, Pandas, NumPy
- Scikit-learn (Random Forest, metrics)
- Matplotlib, Seaborn
- Joblib (model saving)

---

## 🚀 Workflow

1. Load and parse data from `covtype.data.gz`
2. Assign column headers (based on UCI description)
3. Train/test split (80/20)
4. Train a Random Forest Classifier
5. Save model to `forest_model.pkl`
6. Evaluate with accuracy, confusion matrix, and classification report

---

## 📈 Output

- Printed accuracy score (e.g., 94%)
- Confusion matrix heatmap
- Classification report (precision, recall, f1-score)

---

## 📝 Author

**Syed Muhammad Hammad Irshad**  
Elevvo Internship Submission (Task 3 - August 2025)

---
