# Brain Tumor Classification using VGG16

This repository contains a deep learning project for **brain tumor classification** using the **VGG16** model.  
The model is trained on a **custom multi-class dataset** containing four categories of brain MRI scans.

---

## Project Overview

This project demonstrates how transfer learning with **VGG16** can be used for **multi-class tumor classification**.  
The notebook (`TumorDetection_TRAIN.ipynb`) covers data loading, preprocessing, model training, evaluation, and visualization.

---

## Features

- Multi-class classification (4 tumor types)  
- Transfer Learning using pretrained **VGG16** (ImageNet weights)  
- Custom dataset integration  
- Data augmentation for robustness  
- Confusion matrix and performance plots  
- Easily adaptable to new medical datasets

---

## Tech Stack

- **Python 3.x**  
- **TensorFlow / Keras**  
- **NumPy**  
- **Matplotlib**  
- **OpenCV**  
- **scikit-learn**

---

## Dataset Description

https://www.kaggle.com/datasets/sartajbhuvaji/brain-tumor-classification-mri?resource=download

The dataset contains MRI images of four brain tumor types:

| Tumor Type | Folder Name | Description |
|-------------|--------------|-------------|
| Glioma Tumor | `glioma_tumor/` | Glioma-type brain tumor images |
| Meningioma Tumor | `meningioma_tumor/` | Meningioma-type brain tumor images |
| Pituitary Tumor | `pituitary_tumor/` | Pituitary-type brain tumor images |
| No Tumor | `no_tumor/` | Normal brain MRI images |

**Dataset Path Example:**
```
/content/drive/MyDrive/VSD/archive/
├── glioma_tumor/
├── meningioma_tumor/
├── no_tumor/
└── pituitary_tumor/
```

You can easily replace this dataset with any other MRI dataset following the same folder structure.


### Training Curves
The notebook visualizes:
- Training vs. Validation Accuracy  
- Training vs. Validation Loss

---

## Getting Started

### 1. Clone the repository
```bash
git clone https://github.com/<your-username>/TumorDetection.git
cd TumorDetection
```

### 2. Install dependencies
```bash
pip install -r requirements.txt
```

If `requirements.txt` is not available:
```bash
pip install tensorflow keras numpy matplotlib opencv-python scikit-learn
```

### 3. Update dataset path
In the notebook, update your dataset directory path:
```python
dataset_path = "/content/drive/MyDrive/VSD/archive/"
```

### 4. Run the notebook
```bash
jupyter notebook TumorDetection_TRAIN.ipynb
```



## 👨‍💻 Author

**Dr.D.Dinesh Kumar, ASP/ECE, Mepco Schlenk Engineering College **  
