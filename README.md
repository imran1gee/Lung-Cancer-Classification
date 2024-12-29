# Lung Cancer Classification with CNNs

This project utilizes Convolutional Neural Networks (CNNs) to classify lung CT scan images into different categories such as adenocarcinoma, large cell carcinoma, squamous cell carcinoma, and normal cases.

## Project Overview
- **Dataset**: The dataset used for this project consists of lung CT scans, structured into `train`, `test`, and `valid` folders.
- **Objective**: To classify lung images into the correct category using deep learning.
- **Model**: A CNN built with Keras and TensorFlow.

## Results
The model achieved a classification accuracy of **56%** on the test set.

### Confusion Matrix
| **True \ Predicted** | Adenocarcinoma | Large Cell | Normal | Squamous Cell |
|-----------------------|----------------|------------|--------|---------------|
| Adenocarcinoma        | 105            | 0          | 4      | 11            |
| Large Cell            | 38             | 0          | 3      | 10            |
| Normal                | 0              | 0          | 54     | 0             |
| Squamous Cell         | 68             | 0          | 6      | 16            |

---
The project includes several visual outputs saved as PDF files in the results/ folder:

Confusion matrix plot.
Loss and accuracy curves during training.
Classification report metrics.
### Key Performance Metrics:
Accuracy: 56%
Precision, Recall, F1-Score: Available in the classification report.
The results indicate areas for improvement in the model performance.

### File Structure


