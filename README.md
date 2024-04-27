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

**Links to Training Data:**
- [1.1_age_input_output](https://drive.google.com/drive/folders/1tYXOGJZqFljAyC6gqsSusHtDe2oh-PJo?usp=drive_link)
- [1.2 _gender_input_output](https://drive.google.com/drive/folders/1qe_HzoRFPb0MSlr1c40k3lPam6xJGHSs?usp=drive_link)
- [1.3_emotion _input_out](https://drive.google.com/drive/folders/1Mk-4DWA9d2a9n6C8ygG8FUKvVqmfbAzP?usp=drive_link)
- [1.4_test_input](https://drive.google.com/drive/folders/14hHc5vWHe51NtYA4eRr7sj2HWjkYhZLB?usp=drive_link)


## Solution Approach

**Deep Learning with CNNs:**
- Convolutional Neural Networks (CNNs) are used for image analysis.
- Pre-trained CNN models (provided) handle feature extraction and pre-processing automatically.

**Model Deployment:**
- Trained CNN models are deployed at the store entrance to analyze customer images.

## Implementation Steps

1. Load Pre-trained Models:
   - Utilize provided pre-trained models.
   
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

