# Sign Language Recognition using Machine Learning

![Sign Language](https://d.newsweek.com/en/full/1394686/asl-getty-images.webp?w=737&f=991648c2c30074c7b42f25aec96e9e40)

This project aims to develop a system that can accurately recognize and classify American Sign Language (ASL) gestures from images using machine learning techniques. 

## Project Overview

The project explores various classification algorithms including:

- **k-Nearest Neighbors (kNN)**
- **Support Vector Machine (SVM)**
- **Random Forest**
- **Convolutional Neural Network (CNN)**

These algorithms are trained and evaluated on the Sign Language MNIST dataset, which contains images of hand gestures representing letters from the alphabet (excluding J and Z).

## Dataset

The project uses the Sign Language MNIST dataset, which can be found [Kaggle](https://www.kaggle.com/datasets/datamunge/sign-language-mnist/data). 

## Methodology

1. **Data Loading and Preprocessing:** The dataset is loaded, and images are preprocessed (normalized, reshaped) for model training.
2. **Model Training and Evaluation:** Different machine learning models (kNN, SVM, Random Forest, CNN) are trained and evaluated on the dataset. Accuracy, precision, recall, and F1-score are used as evaluation metrics.
3. **Model Selection:** The best-performing model is selected based on the evaluation results.
4. **Testing and Visualization:** The selected model is tested on a set of sample images, and the results are visualized.

## Results

The project achieves an accuracy of [80%] using the [Random Forest] model.
