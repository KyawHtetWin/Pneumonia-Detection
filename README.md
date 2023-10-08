# Pneumonia Detection Project

## Overview
This project consists of two parts: pneumonia detection using the VGG16 and MobileNet models. The primary objective is to detect pneumonia in chest X-ray images, and the project includes the following components:

1. **Data Collection and Preparation:** The project uses a dataset containing chest X-ray images categorized into "Normal" and "Pneumonia" classes. These images are divided into training, validation, and test sets to facilitate model training and evaluation.

2. **Model Building:** Two deep learning models, VGG16 and MobileNet, are utilized for pneumonia detection. Transfer learning is employed, starting with pre-trained models on the ImageNet dataset.

3. **Data Augmentation:** To enhance model performance and generalize its ability to recognize patterns, data augmentation techniques like rotation, width and height shifts, shear, zoom, and horizontal flip are applied to the training dataset.

4. **Model Training:** Both models are trained on the augmented training dataset. Training progress is monitored using validation data to prevent overfitting.

5. **Model Evaluation:** The models' performance is evaluated using the test dataset, which was not seen during training. Evaluation metrics include accuracy, a confusion matrix, and a classification report.

6. **Comparison:** A comparison is made between the VGG16 and MobileNet models in terms of training and validation accuracy.

## Files
- `Pneumonia Detection.ipynb`: The Jupyter Notebook containing the code for the entire project, including data preprocessing, model building, training, and evaluation.

## Usage
1. Open the `Pneumonia Detection.ipynb` Jupyter Notebook in an environment that supports Python and deep learning libraries.
2. Execute each cell sequentially to load and preprocess the data, build and train the models, and evaluate their performance.
3. Examine the results, including accuracy, confusion matrix, and classification report, to assess the models' performance.

## Dependencies
- The project utilizes various Python libraries, including Keras, Matplotlib, NumPy, and scikit-learn. Ensure that these libraries are installed in your environment to run the code successfully.

## Results
The project includes a comparison of the VGG16 and MobileNet models' performance in terms of training and validation accuracy. Additionally, it presents the accuracy achieved on the test dataset and visualizations of the confusion matrix and classification report.
