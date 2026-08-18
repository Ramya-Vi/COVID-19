# COVID-19

COVID-19 Image Classification Using CNN
📌 Project Overview

This project uses Deep Learning and Convolutional Neural Networks (CNN) to classify chest X-ray images into two categories:

COVID-19
Normal

The main purpose of this project is to automatically classify chest X-ray images and support early detection of COVID-19.

🎯 Problem Statement

Manual analysis of chest X-ray images can be time-consuming and requires experienced radiologists. This project aims to develop a CNN model that can automatically classify chest X-ray images as COVID-19 or Normal.

🎯 Objectives
Build a CNN model for COVID-19 detection.
Preprocess chest X-ray images.
Compare different CNN models.
Evaluate model performance.
Predict COVID-19 using unseen X-ray images.
📊 Dataset

The dataset contains chest X-ray images belonging to two classes:

COVID-19
Normal

All images are resized to 128 × 128 pixels before training the model.

The project loads:

CovidImages.npy – Image dataset
CovidLabels.csv – Image labels
🛠️ Technologies Used
Python
NumPy
Pandas
OpenCV
Matplotlib
Seaborn
TensorFlow
Keras
Scikit-learn
Google Colab
🤖 Machine Learning / Deep Learning

A Convolutional Neural Network (CNN) is used for image classification.

The project uses CNN-related layers including:

Conv2D
MaxPooling2D
Flatten
Dense
Dropout

TensorFlow/Keras is used to build the deep learning model.

🔄 Project Workflow
Chest X-ray Images
        ↓
Data Loading
        ↓
Image Preprocessing
        ↓
Image Resizing (128 × 128)
        ↓
Train-Test Split
        ↓
CNN Model
        ↓
Model Training
        ↓
Model Evaluation
        ↓
COVID-19 / Normal Prediction
📈 Model Evaluation

The project evaluates the classification model using:

Classification Report
Confusion Matrix

These metrics are used to understand the performance of the CNN model.

💡 Expected Outcome

The expected outcome is a CNN model capable of accurately classifying chest X-ray images into COVID-19 and Normal categories and assisting in early detection.

📁 Project Structure
COVID-19-Image-Classification/
│
├── covid_19.ipynb
├── CovidImages.npy
├── CovidLabels.csv
├── README.md
└── requirements.txt
🚀 How to Run
1. Open the project in Google Colab

Upload covid_19.ipynb to Google Colab.

2. Upload the dataset

Make sure the following files are available:

CovidImages.npy
CovidLabels.csv
3. Mount Google Drive

The notebook connects Google Drive to access the dataset.

4. Run the notebook

Execute the cells sequentially to preprocess the images, train the CNN model, evaluate its performance, and make predictions.

🔮 Future Improvements
Use transfer learning models such as VGG16, ResNet, or MobileNet.
Increase the size and diversity of the dataset.
Apply data augmentation.
Perform hyperparameter tuning.
Develop a web-based COVID-19 image classification application.
⚠️ Disclaimer

This project is developed for educational and research purposes only. It should not be used as a substitute for professional medical diagnosis.
