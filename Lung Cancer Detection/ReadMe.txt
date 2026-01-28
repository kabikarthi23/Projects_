# Lung Cancer Detection Using CNN

This project focuses on detecting lung cancer from histopathologic images using a Convolutional Neural Network (CNN). The model was trained on the LC25000 dataset and aims to support early diagnosis by classifying cancerous and non-cancerous tissue images.

## 🧠 Project Objectives
- Build and train a CNN model for binary image classification.
- Use Grad-CAM for visualizing key areas influencing the model's decision.
- Evaluate the model performance using accuracy and classification metrics.

## 🗂️ Dataset
- **LC25000 Dataset** – Histopathologic lung tissue images labeled as benign or malignant.
- Dataset contains 25,000 images of lung tissue in different categories.

## 🔧 Technologies Used
- Python
- TensorFlow / Keras
- NumPy, Pandas
- Matplotlib, Seaborn
- Grad-CAM (for model explainability)

## 📊 Model Performance
- Accuracy: **94%**
- Training: 80% training set, 20% test set
- Optimizer: Adam
- Loss: Binary Crossentropy

## 📌 Key Features
- Preprocessed and augmented image data
- Custom CNN architecture with Conv2D, MaxPooling, and Dense layers
- Used EarlyStopping to avoid overfitting
- Integrated Grad-CAM for model interpretability

## 📸 Grad-CAM Visualizations
<p align="center">
  <img src="path_to_gradcam_image.png" width="400"/>
</p>

## 🔍 Conclusion
This project demonstrates the potential of deep learning in medical image analysis. With further refinement and clinical validation, such models can assist in diagnostic workflows.

## 🔗 Project Links
- [LC25000 Dataset Info](https://www.kaggle.com/datasets/andrewmvd/lung-and-colon-cancer-histopathological-images)
- [LinkedIn Post](#)
