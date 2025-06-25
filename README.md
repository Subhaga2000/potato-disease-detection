# 🍃 Potato Leaf Disease Detection - CNN Model (Improved)

This project uses a **Convolutional Neural Network (CNN)** to classify potato leaf diseases into three classes:

- Potato___Healthy
- Potato___Early_Blight
- Potato___Late_Blight

### ✅ Updates in this Improved Version

- Increased model depth (more Conv2D layers)
- Added dropout layers for regularization
- Added data augmentation (flip, rotation)
- Used smaller image size (128x128) for efficiency
- Applied early stopping and learning rate scheduler

### 🧪 Achieved Results

| Metric | Accuracy |
|--------|----------|
| Training Accuracy | 97.4% |
| Validation Accuracy | 97.1% |
| Test Accuracy | 97.8% |

### 📁 Notebook File

- `Potato_Leaf_Disease_Detection_CNN.ipynb`

### 📚 Dataset

- Source: [PlantVillage dataset (Kaggle)](https://www.kaggle.com/datasets/emmarex/plantdisease)

---

### 📌 How to Run

1. Clone this repo or upload the notebook to Google Colab.
2. Install dependencies:
```bash
pip install tensorflow matplotlib
