# MelanoTrack

**Making Melanoma Awareness and Skin Health Monitoring More Accessible**

MelanoTrack is a native iOS application developed for the 2026 Congressional App Challenge.

## About the Project

MelanoTrack aims to help individuals recognize potential warning signs of melanoma, document skin changes, and prepare information to discuss with healthcare professionals.

## Features

- Guided skin scans with an interactive body map
- Photo capture and upload
- ABCDE melanoma assessment
- Experimental machine-learning image classification
- Doctor summaries
- Saved scan history
- Melanoma education
- Accessibility settings

## Technologies

- Swift and SwiftUI
- Python and PyTorch
- Core ML
- Xcode
- Kaggle skin lesion dataset

## Machine Learning

The image-classification model was trained using over 10,000 labeled skin lesion images.

On a held-out test set, the model achieved 91.6% classification accuracy. However, it still misclassified malignant images, demonstrating the limitations of using accuracy alone.

MelanoTrack uses uncertainty-aware classification to flag predictions with insufficient confidence.

**Important:** The model is experimental, has not been clinically validated on ordinary iPhone photographs, and cannot diagnose or rule out melanoma. It is not a substitute for professional medical evaluation.

## Developer

Aarav Gulati

2026 Congressional App Challenge
