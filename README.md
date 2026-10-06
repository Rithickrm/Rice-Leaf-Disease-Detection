# Rice Leaf Disease Detection Using CNN

## Project Overview

Rice Leaf Disease Detection is a deep learning project that uses Convolutional Neural Networks (CNN) to identify diseases in rice leaves from images.

The project compares a Baseline CNN model with an Augmented CNN model to improve disease classification performance.

## Objectives

- Detect diseases in rice leaf images.
- Preprocess and prepare image data for CNN training.
- Build and train a Baseline CNN model.
- Apply image augmentation techniques.
- Build and train an Augmented CNN model.
- Compare model performance.
- Evaluate predictions using classification metrics and confusion matrices.

## Technologies Used

- Python
- TensorFlow
- Keras
- NumPy
- Pandas
- Scikit-learn
- Matplotlib
- Seaborn
- Pillow
- Google Colab

## Project Workflow

1. Dataset Collection
2. Image Preprocessing
3. Image Resizing
4. Label Encoding
5. Train-Test Split
6. Baseline CNN Development
7. CNN Model Training
8. Image Data Augmentation
9. Augmented CNN Development
10. Model Evaluation
11. Confusion Matrix Analysis
12. Model Comparison
13. Final Prediction

## Models

### Baseline CNN

A Convolutional Neural Network was developed as the baseline model for classifying rice leaf diseases.

### Augmented CNN

Image augmentation techniques were applied to improve model generalization.

The augmentation techniques include:

- Rotation
- Width Shifting
- Height Shifting
- Zooming
- Horizontal Flipping

## Results

The project evaluates both Baseline CNN and Augmented CNN models using:

- Accuracy
- Classification Report
- Confusion Matrix
- Prediction Results

The final prediction results are stored in:

`rice_leaf_final_results.csv`

Augmented CNN prediction results are stored in:

`rice_leaf_augmented_prediction_results.csv`

## Project Structure

```text
Rice-Leaf-Disease-Detection/
│
├── Models/
│   ├── Results/
│   └── README.md
│
├── Src/
│   └── app.py
│
├── Rice_Leaf_Disease_Detection.ipynb
├── rice_leaf_augmented_prediction_results.csv
├── rice_leaf_class_labels.json
├── rice_leaf_final_results.csv
├── requirements.txt
└── README.md
