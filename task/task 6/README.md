
# Task 6: Music Genre Classification - Elevvo Internship

This project classifies music genres using audio features (MFCCs) extracted from 30-second clips in the GTZAN dataset. A deep learning model (MLP) is trained on tabular features to predict one of 10 music genres.

---

## 📁 Project Structure

```
task 6/
├── code.ipynb                  # Main notebook
├── Data/
│   ├── features_30_sec.csv     # Tabular MFCC feature data
│   ├── genres_original/        # (Optional) Audio files
│   └── images_original/        # (Optional) Spectrograms
├── music_genre_model.h5        # Trained Keras model
├── label_encoder.pkl           # Encoded genre labels
└── README.md                   # This file
```

---

## 📦 Dataset

Source: [GTZAN Dataset (Kaggle)](https://www.kaggle.com/datasets/andradaolteanu/gtzan-dataset-music-genre-classification)

- 10 genres (pop, rock, classical, etc.)
- 100 audio tracks per genre (30 seconds each)
- MFCC feature CSV provided as `features_30_sec.csv`

---

## ⚙️ Tools Used

- Python, Pandas, NumPy
- TensorFlow / Keras (MLP model)
- Scikit-learn (metrics, preprocessing)
- Joblib (label encoder)
- Matplotlib & Seaborn (visualizations)

---

## 🚀 Workflow

1. **Data Loading** – Read features from `features_30_sec.csv`
2. **Preprocessing** – Encode labels, scale features
3. **Modeling** – Train an MLP on MFCCs
4. **Saving** – Model saved as `music_genre_model.h5`, encoder as `label_encoder.pkl`
5. **Evaluation** – Confusion matrix + classification report

---

## 📈 Output

- Final accuracy printed after evaluation
- Confusion matrix of predicted vs true genres
- Classification report with precision/recall

---

## 📝 Author

**Syed Muhammad Hammad Irshad**  
Elevvo Internship Submission (Task 6 - August 2025)

---
