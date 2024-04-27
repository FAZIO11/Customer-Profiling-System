# Customer Profiling System with Deep Learning

This project demonstrates a customer profiling system designed to capture demographics (age, gender, emotion) using deep learning techniques.

## Project Goal

Build a system to analyze customer demographics upon entering a retail store.

## Benefits

- Improved inventory management through customer insights.
- Targeted promotions based on customer profiles.
- Enhanced customer experience through data-driven personalization.

## Data Requirements

- Large datasets of labelled images for age, gender, and emotion recognition.
- Public datasets like UTK Faces and CK+ are recommended.

**[Link to Training Data on Google Drive](insert_link_here)**

## Solution Approach

**Deep Learning with CNNs:**
- Convolutional Neural Networks (CNNs) are used for image analysis.
- Pre-trained CNN models (provided) handle feature extraction and pre-processing automatically.

**Model Deployment:**
- Trained CNN models are deployed at the store entrance to analyze customer images.

## Implementation Steps

1. Load Pre-trained Models (or Train Your Own):
   - Utilize provided pre-trained models or train custom models if desired.
   
2. Image Prediction Script:
   - A script is included to load the models and predict demographics from test images.

3. Face Detection Integration:
   - Haar cascade classifier is used to identify faces within images before feeding them to the models.

## Results

The system achieves an accuracy of approximately:
- 83% for age recognition.
- 90% for gender recognition.
- 97% for emotion recognition.

## Deliverables

- Pre-trained CNN models for age, gender, and emotion recognition.
- Script showcasing model performance on sample images.

## Overall

This project provides a practical example of building a customer profiling system with deep learning and computer vision. It offers pre-trained models and demonstrates their effectiveness for customer demographic analysis.

