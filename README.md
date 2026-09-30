# 🌿 Cassava Leaf Disease Classification

A Deep Learning project using **PyTorch and Convolutional Neural Networks (CNNs)** to classify cassava leaf images into five disease categories.

The project focuses on building an end-to-end image classification pipeline, from dataset exploration and preprocessing to model training and evaluation.

## 🎯 Project Objective

Cassava is an important food crop, and leaf diseases can significantly affect its production.

The objective of this project is to develop a deep learning model capable of identifying cassava leaf diseases from images, helping explore how computer vision can support agricultural disease detection.

## 📂 Dataset

**Dataset:** [Cassava Leaf Disease Classification – Kaggle](https://www.kaggle.com/competitions/cassava-leaf-disease-classification)

- Total Images: 21,397
- Image Dimensions: 800 × 600
- Color Mode: RGB
- Number of Classes: 5

### Disease Classes

| Label | Disease |
|---|---|
| 0 | Cassava Bacterial Blight (CBB) |
| 1 | Cassava Brown Streak Disease (CBSD) |
| 2 | Cassava Green Mottle (CGM) |
| 3 | Cassava Mosaic Disease (CMD) |
| 4 | Healthy |

## 🛠️ Tech Stack

- Python
- PyTorch
- Torchvision
- NumPy
- Pandas
- Matplotlib
- Scikit-learn
- Pillow

## 📊 Project Workflow

### Phase 1: Exploratory Data Analysis
- Dataset inspection
- Class distribution analysis
- Identification of class imbalance
- Image dimensions and color mode verification
- Visualization of samples from all five classes

### Phase 2: Data Pipeline
- Train-validation split using stratified sampling
- Custom PyTorch Dataset implementation
- Image loading and tensor conversion
- DataLoader implementation
- Batch shape and datatype verification

### Phase 3: Image Preprocessing
- Image resizing
- Channel-wise normalization
- Data augmentation

### Phase 4: Model Development
- CNN architecture
- Model training
- Loss and optimizer selection

### Phase 5: Evaluation
- Accuracy
- Precision
- Recall
- F1-score
- Confusion matrix

### Phase 6: Future Improvements
- Transfer learning
- Model optimization
- Inference on unseen images
- Deployment

## 📈 Dataset Insights

- The dataset contains five cassava leaf categories.
- Cassava Mosaic Disease (Class 3) represents approximately 61.49% of the training dataset.
- The dataset is imbalanced, making class-wise evaluation important.
- All inspected images have consistent dimensions of 800 × 600 pixels and RGB color mode.

## 📁 Project Structure

```text
Cassava-Leaf-Disease-Classification/
│
├── data/
│   └── raw/
│       ├── train_images/
│       ├── test_images/
│       ├── train.csv
│       └── label_num_to_disease_map.json
│
├── notebooks/
│   └── data_exploration.ipynb
│
├── src/
│
├── requirements.txt
├── .gitignore
└── README.md
```

*The structure will evolve as the project progresses.*

## 🚀 Current Progress

**Status:** Data Pipeline Development

Currently completed:
- Dataset exploration
- Class distribution analysis
- Image inspection
- Stratified train-validation split
- Custom Dataset class
- DataLoader and batch verification
- Image resizing exploration

Model training and evaluation are upcoming stages.

## 👨‍💻 Author

**Rushabh Borkar**

B.Tech CSE (AI & ML) Student

- GitHub: [rushabh-borkar](https://github.com/rushabh-borkar)
- LeetCode: [LunarX](https://leetcode.com/u/LunarX/)

---

⭐ If you find this project interesting, feel free to explore the repository.
