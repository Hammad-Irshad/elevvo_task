
# 🚦 Task 8: Traffic Sign Recognition - Elevvo Internship

This project uses a Convolutional Neural Network (CNN) built with TensorFlow/Keras to classify German traffic signs using the **GTSRB** dataset. It is part of the Elevvo Internship Task 8 submission.

---

## 📂 Project Structure

```
task 8/
├── code.ipynb                # Main notebook
├── traffic_sign_model.h5     # (Optional) Pre-trained model
├── README.md                 # You're here
├── Train/                    # Training images (43 class folders) - NOT pushed to GitHub
└── .gitignore                # To exclude dataset from version control
```

---

## 🧠 Dataset

- **German Traffic Sign Benchmark (GTSRB)**
- Preprocessed Dataset from Kaggle:  
  🔗 https://www.kaggle.com/datasets/meowmeowmeowmeowmeow/gtsrb-german-traffic-sign
  

After downloading, place the contents in:

```
task 8/
├── Train/
│   ├── 0/
│   ├── 1/
│   ├── ...
```

---

## 📦 Requirements

Install dependencies using pip:

```bash
pip install numpy pandas matplotlib scikit-learn opencv-python tensorflow
```

You can also use:

```bash
pip install -r requirements.txt  # If provided
```

---

## 🚀 How to Run

1. Place the `Train/` folder inside the same directory as `code.ipynb`
2. Run the notebook in VS Code or Jupyter:

```bash
jupyter notebook code.ipynb
```

3. The model will either:
   - Load the pre-trained file: `traffic_sign_model.h5` ✅
   - Or train from scratch if not found ❌

---

## 🧪 Features

- CNN architecture: Conv2D → MaxPooling → Dense
- Image preprocessing and normalization
- Model checkpointing with `.h5` file
- Visual performance: Accuracy & Loss graphs
- Evaluation: Confusion matrix + classification metrics

---

## 📊 Results

- Accuracy achieved: **~94–97%** (depends on training)
- Over 39,000 images used from 43 traffic sign classes

---

## 📝 Notes

- Dataset and image folders are large and excluded from GitHub via `.gitignore`
- You can retrain the model by deleting the `.h5` file or forcing `model.fit()`

---

## 🏁 Author

**Syed Muhammad Hammad Irshad**  

