# Garbage Classification Project

## Objective

Classify garbage images into 6 categories: cardboard, glass, metal, paper, plastic, and trash using deep learning.

## Dataset

- **Source**: [Kaggle - Trash Type Image Dataset](https://www.kaggle.com/datasets/farzadnekouei/trash-type-image-dataset)
- **Total Images**: ~2400
- **Format**: Folder-wise (one per class)

## Tools Used

- Python
- TensorFlow / Keras
- EfficientNetV2B2 (Transfer Learning)
- Scikit-learn
- Gradio
- Hugging Face Spaces

## Week 1 Progress (30%)

- Set up the TensorFlow environment
- Downloaded and structured the dataset
- Created a test script using MobileNetV2
- Trained and saved the model as `garbage_classifier.h5`

## Week 2 Progress (60%)

- Switched to EfficientNetV2B2 for improved accuracy
- Implemented data augmentation & class weights to handle imbalance
- Trained the model with early stopping and learning rate scheduler
- Evaluated model performance using confusion matrix and classification report
- Saved the model as `efficientnetv2b2_model.keras`
- Built a Gradio interface for image upload & prediction
- Deployed the app on Hugging Face: [Live Demo](https://huggingface.co/spaces/Sayemkhan1111/sayem-garbage-classifier)

## Week 3 Progress (Final - 100%)

- Fine-tuned deeper layers of EfficientNetV2B2 for better accuracy
- Used callbacks: EarlyStopping, ReduceLROnPlateau for optimized training
- Achieved training accuracy ~98% and validation accuracy ~90%
- Evaluated model performance with confusion matrix and classification report
- Visualized accuracy and loss curves for training and validation sets
- Saved the final model as `efficientnetv2b2_model.keras`
- Enhanced the Gradio UI with a user-friendly interface for live predictions
- Successfully deployed the Gradio app on Hugging Face Spaces for public access

## Project Completed

A robust and accurate classification model has been developed and deployed for public access.
