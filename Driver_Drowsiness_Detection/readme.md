# Driver Drowsiness Detection 

## Overview
The project aims to identify and classify driver drowsiness using deep learning models, specifically Transfer Learning and Convolutional Neural Network with Parallel Convolution Architecture.

## Dataset
The dataset used for training and evaluation is the "Driver Drowsiness Dataset (DDD)." It consists of images categorized as drowsy and non-drowsy.

## Code Structure
- **Data Preparation:**
  - The dataset is organized into two categories: drowsy and non-drowsy.
  - Dataframes are created to manage file paths and labels.
  - Data distribution is visualized using a count plot.

- **Data Augmentation and Splitting:**
  - ImageDataGenerator is used for data augmentation.
  - The dataset is split into training, validation, and test sets using `train_test_split`.

- **Model Architecture:**
  - Transfer Learning is implemented using InceptionResNetV2.
  - A custom CNN architecture with Parallel Convolution layers.
  - The models are compiled with Adamax optimizer and categorical crossentropy loss.

- **Training:**
  - The model is trained for a specified number of epochs.
  - Training and validation accuracy/loss are visualized using plots.

- **Evaluation:**
  - Model performance is evaluated on the training, validation, and test sets.
  - Classification report and confusion matrix are generated.

- **Prediction and Visualization:**
  - Sample images are provided to demonstrate model predictions.
  - Activation maps and Grad-CAM visualizations are implemented for interpretability.


## Requirements
- Python 
- TensorFlow
- Pandas
- Matplotlib
- Seaborn
- OpenCV
- PIL

## Results
The project achieved promising results in terms of accuracy and provides visualizations to aid in model interpretation.

|  Model | Accuracy |
|----------|----------|
| Transfer Learning | 99.73% |
| Custom CNN | 99.90% |

## Maintainer
This repository is maintained by Nithish Chowdary.

**Nithish Chowdary**
Senior Python Developer / AI/ML Engineer
- Email: nithishmc1@gmail.com
- GitHub: https://github.com/NithishChowdary-Python-Dev
- LinkedIn: http://www.linkedin.com/in/nithishchowdary-python

## About the Developer
Nithish Chowdary is a Senior Python Developer and AI/ML Engineer with over 10 years of experience designing, building, and deploying scalable machine learning models and advanced analytics solutions. His expertise spans deep learning, computer vision, and backend architecture, with a focus on creating robust AI-driven applications.