# ClassifierCodeLBP
Image Classification using Local Binary Patterns

 

---

# Image Classification using Local Binary Patterns (LBP)

This project demonstrates image classification using the **Local Binary Patterns (LBP)** method. It is designed to classify images into two categories: **cats** and **dogs**. The classification is performed using a **Support Vector Machine (SVM)** model.

## Dataset
The dataset used in this project consists of **100 images**:
- **50 images of cats**
- **50 images of dogs**

## Features
- **Feature Extraction**: Local Binary Patterns (LBP) are applied to extract texture-based features from the images.
- **Classification Model**: Support Vector Machine (SVM) is used for classifying the extracted features into cats or dogs.
- **Evaluation**: Model accuracy and performance metrics are computed to evaluate the classifier.

## Requirements
To run the project, ensure you have the following installed:
- Python 3.x
- Jupyter Notebook
- Required Python libraries:
  - NumPy
  - OpenCV
  - scikit-learn
  - matplotlib (optional, for visualizations)

Install the dependencies using pip:
```bash
pip install numpy opencv-python scikit-learn matplotlib
```


## Project Workflow
1. **Preprocessing**: Load and preprocess the dataset images.
2. **Feature Extraction**: Extract LBP features from the images.
3. **Model Training**: Train the SVM classifier using the extracted features.
4. **Evaluation**: Test the classifier on a test set and evaluate its performance.

## Results
The SVM classifier achieved notable accuracy in distinguishing between cats and dogs using LBP features.

## Acknowledgments
- **Local Binary Patterns**: A feature extraction technique commonly used in texture analysis.
- **Support Vector Machine (SVM)**: A powerful classifier for binary classification tasks.


---

Let me know if you’d like to add or modify anything!
