# Rice Leaf Disease Detection Using CNN

## Project Overview

This project focuses on detecting and classifying rice leaf diseases using Convolutional Neural Networks (CNN). The model analyzes rice leaf images and predicts the corresponding disease class.

Two CNN approaches were developed and compared:

- Baseline CNN
- Augmented CNN

Data augmentation techniques were applied to improve the model's ability to generalize to different rice leaf images.

## Objectives

- Detect diseases from rice leaf images.
- Build a CNN-based image classification model.
- Apply image preprocessing and data augmentation.
- Compare Baseline CNN and Augmented CNN performance.
- Identify the best-performing model.

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

1. Dataset collection
2. Image preprocessing
3. Image resizing
4. Label encoding
5. Train-test splitting
6. CNN model development
7. Model training
8. Data augmentation
9. Model evaluation
10. Confusion matrix analysis
11. Model comparison
12. Final model selection

## Models

### Baseline CNN

A CNN model was developed using convolution, max-pooling, flattening and dense layers.

### Augmented CNN

The second model used image augmentation techniques such as:

- Rotation
- Width shifting
- Height shifting
- Zooming
- Horizontal flipping

The performance of both models was compared using test accuracy and test loss.

## Results

The final model results are available in:

`rice_leaf_final_results.csv`

Prediction results are available in:

`rice_leaf_augmented_prediction_results.csv`

## Project Structure

```text
Rice-Leaf-Disease-Detection/
│
├── Models/
├── Results/
├── Notebook/
├── Src/
│   └── app.py
│
├── README.md
└── requirements.txt

```

## Conclusion

The Rice Leaf Disease Detection project was successfully developed using Convolutional Neural Networks. Both Baseline CNN and Augmented CNN models were trained and evaluated. Data augmentation was used to improve model generalization, and the models were compared based on their test performance.

The best-performing model was selected based on the actual test accuracy and loss obtained during evaluation.

## Future Improvements

- Deploy the model as a web application.
- Use a larger rice leaf image dataset.
- Experiment with transfer learning models such as MobileNet, EfficientNet and ResNet.
- Improve prediction accuracy with further hyperparameter tuning.

## Author

**Rithick M**
