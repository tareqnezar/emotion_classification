# Emotion Recognition with LeNet

A deep learning model that classifies facial expressions as **Angry**, **Happy**, or **Sad** using a LeNet-5 CNN.

## Results
- **Validation Accuracy:** 72.5%
- **Top-2 Accuracy:** 90.3%

## Dataset
- 6,799 training images
- 2,278 validation images
- 3 emotion classes

## Model Architecture
- 2 Convolutional layers (6 → 16 filters)
- Batch Normalization
- MaxPooling
- 2 Dense layers (100 → 10 → 3)
- ~6.1 million parameters

