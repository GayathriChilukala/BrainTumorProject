# 🧠 Brain Tumor Detection & Classification

A deep learning project for brain tumor detection and classification using MRI images.

## Overview

This project leverages convolutional neural networks (CNNs) to analyze brain MRI scans and classify tumors. Early and accurate detection of brain tumors is critical for treatment planning and improving patient outcomes.

## Features

- **Tumor Detection** – Identifies the presence of brain tumors in MRI scans
- **Classification** – Categorizes tumor types (e.g., glioma, meningioma, pituitary, no tumor)
- **Image Preprocessing** – Includes normalization, resizing, and augmentation pipelines
- **Model Evaluation** – Accuracy, confusion matrix, and classification reports

## Dataset

The model is trained on brain MRI image datasets. Images are organized by tumor type and split into training and testing sets.

> **Note:** Due to size constraints, the dataset is not included in this repository. You can download it from [Kaggle – Brain Tumor MRI Dataset](https://www.kaggle.com/datasets/masoudnickparvar/brain-tumor-mri-dataset).

## Tech Stack

- **Python**
- **TensorFlow / Keras** – Model building and training
- **NumPy / Pandas** – Data manipulation
- **Matplotlib / Seaborn** – Visualization
- **OpenCV / PIL** – Image processing
- **scikit-learn** – Model evaluation metrics
- **Jupyter Notebook** – Development environment

## Getting Started

### Prerequisites

```bash
pip install tensorflow numpy pandas matplotlib seaborn opencv-python scikit-learn pillow
```

### Running the Notebook

1. Clone the repository:
   ```bash
   git clone https://github.com/GayathriChilukala/BrainTumorProject.git
   cd BrainTumorProject
   ```

2. Launch Jupyter Notebook:
   ```bash
   jupyter notebook GayathriChilukala.ipynb
   ```

3. Follow the cells in order to:
   - Load and preprocess the data
   - Build and train the CNN model
   - Evaluate performance on the test set
   - Visualize predictions

## Model Architecture

The project uses a Convolutional Neural Network (CNN) with:
- Multiple convolutional and pooling layers for feature extraction
- Dropout layers to reduce overfitting
- Dense layers for final classification

## Results

The model is evaluated using:
- **Accuracy** on the test set
- **Confusion Matrix** to visualize prediction performance
- **Classification Report** with precision, recall, and F1-score per class

## Project Structure

```
BrainTumorProject/
│
├── GayathriChilukala.ipynb   # Main notebook with full pipeline
└── README.md                 # Project documentation
```

## Author

**Gayathri Chilukala**  
[GitHub Profile](https://github.com/GayathriChilukala)

## License

This project is open-source and available for educational and research purposes.
