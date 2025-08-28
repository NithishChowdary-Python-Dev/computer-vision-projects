# Traffic Sign Detection and Classification

This repository contains code for traffic sign detection and classification. It includes data preprocessing, feature extraction using Histogram of Oriented Gradients (HOG), training a Random Forest classifier for traffic sign detection, and a deep learning approach using transfer learning and Convolutional Neural Networks (CNNs) for traffic sign classification.

## Data Preprocessing

- Class labels are loaded from CSV files.

- Image data is collected from various classes, and labels are assigned to each image.

- Images are resized and preprocessed for feature extraction and classification.

## Traffic Sign Detection with HOG Features

- Histogram of Oriented Gradients (HOG) features are extracted from each image.

- A Random Forest classifier is trained to detect traffic signs.

- Model performance is evaluated using accuracy and a classification report with class names.

## Data Splitting

- The data is split into training and validation sets for deep learning.

- Data augmentation is applied to the training set for improved model generalization.

## Traffic Sign Classification with Transfer Learning

- Transfer learning is used with the InceptionV3 architecture pre-trained on ImageNet.

- Additional layers are added for traffic sign classification.

- The model is trained and evaluated using the training and validation sets.

## Results

- The Inception based model achieves an accuracy of 97.62%

- The Random Forest classifier achieves an accuracy of 92.07%

## Conclusion

This repository demonstrates a comprehensive workflow for traffic sign detection and classification. It includes traditional machine learning techniques with HOG features and deep learning with transfer learning and CNN models.

## About the Developer

Nithish Chowdary is a Senior Python Developer and AI/ML Engineer with over 10 years of experience designing, building, and deploying scalable machine learning models and advanced analytics solutions. His expertise includes deep learning, computer vision, and building robust microservices using Django, Flask, and FastAPI.

Contact Information:
- Email: nithishmc1@gmail.com
- GitHub: https://github.com/NithishChowdary-Python-Dev
- LinkedIn: http://www.linkedin.com/in/nithishchowdary-python