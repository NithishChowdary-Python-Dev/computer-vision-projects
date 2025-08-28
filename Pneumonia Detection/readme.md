# Pneumonia Detection and Classification

This project contains code for pneumonia detection and classification using various approaches, including machine learning with HOG features and deep learning with CNN models and transfer learning. The implementation loads and preprocesses the Chest X-ray dataset and demonstrates different methods to classify pneumonia and normal images.

## Data Preprocessing

- The Chest X-ray dataset is loaded from the specified directory.

- Images are preprocessed, resized to 128x128 pixels, and augmented to enhance model robustness.

## Pneumonia Detection with HOG Features

- The code computes Histogram of Oriented Gradients (HOG) features for each image.

- A Random Forest classifier is trained on these features to detect pneumonia.

- Model performance is evaluated with accuracy, a classification report, and a confusion matrix.

## Pneumonia Classification with Transfer Learning

- A pre-trained MobileNetV2 model is used as a feature extractor.

- A custom classification head is added to the MobileNetV2 model.

- The model is trained and evaluated for pneumonia classification.

## Pneumonia Classification with Custom CNN Model

- A custom CNN model is created for pneumonia classification.

- The model is trained and evaluated on the same dataset.

## Pneumonia Classification with Autoencoder's Encoder

- An autoencoder is created, and its encoder part is used for feature extraction.

- The extracted features are used for pneumonia classification with a custom classifier.

## Results 

- The CNN model achieved an accuracy of 95.31% 
- MobileNetV2 based model achieved an accuracy of 96.06%
- The Encoder classifier model achieved an accuracy of 92.82%

## Conclusion

This repository provides a comprehensive codebase for pneumonia detection and classification using various approaches. By following this code, users can explore different methods for medical image analysis, including traditional machine learning and deep learning techniques.

## About the Developer

Nithish Chowdary is a Senior Python Developer and AI/ML Engineer with over 10 years of experience designing, building, and deploying scalable machine learning models and advanced analytics solutions. He specializes in deep learning, computer vision, and predictive modeling using TensorFlow, PyTorch, and Scikit-learn.

- GitHub: https://github.com/NithishChowdary-Python-Dev
- LinkedIn: http://www.linkedin.com/in/nithishchowdary-python
- Email: nithishmc1@gmail.com