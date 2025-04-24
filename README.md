Alzheimer's Disease Detection Using CNN Models
This project focuses on classifying MRI brain scans to detect stages of Alzheimer's disease using deep learning. The dataset used is OASIS-1, and the models are trained to classify images into four cognitive categories.

Dataset Name: OASIS-1 (Open Access Series of Imaging Studies)

Source: https://www.kaggle.com/datasets/ninadaithal/imagesoasis

The dataset contains MRI scans labeled into four cognitive conditions representing stages of dementia.

Classification Categories
The models classify brain MRI images into the following four classes:
  1. Non-Demented – Individuals with no signs of dementia.
  2. Very Mild Demented – Subjects showing very early indicators of cognitive decline.
  3. Mild Demented – Subjects with noticeable memory or cognitive issues consistent with mild dementia.
  4. Moderate Demented – Subjects with advanced symptoms and clear clinical signs of dementia progression.

Models Used
The project implements and compares the performance of the following Convolutional Neural Networks: EfficientNetV2B0, EfficientNetV2B1, and ResNet-50. All models were fine-tuned using transfer learning techniques and trained on preprocessed OASIS-1 images resized to 128×128 pixels.
