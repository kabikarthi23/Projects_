# Histopathologic Lung Cancer Detection using CNN

## Project Overview
This project focuses on the **detection of lung cancer from histopathology images** using a **Convolutional Neural Network (CNN)**. Histopathology images are microscopic images of tissue samples used to diagnose diseases such as cancer. Manual examination of these images is time-consuming and requires expert pathologists. This project leverages deep learning to **automatically classify images as cancerous or normal**, assisting in faster and more accurate diagnosis.

The model is trained on the **LC25000 Dataset**, which contains labeled images of lung cancer and normal lung tissue. Using CNNs, the model learns **complex visual patterns and cellular structures** that distinguish cancerous tissue from healthy tissue. Additionally, **Grad-CAM** is applied for interpretability, highlighting the regions in the image that influenced the model’s predictions.

---

## Features
- Automated classification of lung tissue images as cancerous or normal  
- Visual explanation of predictions using Grad-CAM  
- Preprocessing of histopathology images (resizing, normalization, and augmentation)  
- High accuracy in detecting lung cancer from microscopic images  
- Modular and extendable code for further research or clinical integration  

---

## Dataset
- **Name:** LC25000 Dataset  
- **Description:** Contains histopathology images of lung cancer and normal tissue  
- **Usage:** Used for training and validating the CNN model  

---

## Skills and Tools Used
**Programming & Libraries:**  
- Python  
- TensorFlow / Keras or PyTorch  
- NumPy, Pandas  
- Matplotlib, Seaborn  
- OpenCV / PIL for image preprocessing  

**Machine Learning & AI:**  
- Convolutional Neural Networks (CNN)  
- Image classification  
- Data augmentation and preprocessing  
- Grad-CAM for model interpretability  

**Analytical Skills:**  
- Pattern recognition in medical images  
- Translating visual data into actionable insights  

---

## Project Structure
├── inputs/ # Folder containing input histopathology images<br>
├── outputs/ # Folder containing model predictions and Grad-CAM results<br>
├── code.ipynb # Full code file for training and evaluation<br>
├── test.ipynb # Testing file that loads the model and tests results<br>
├── confusion_matrix.png # Confusion matrix image (Normal, ACA, SCC)<br>
├── performance.png # Performance metrics image (Precision, Recall, F1 Score)<br>
├── README.md # Project documentation<br>

---

## Input Example
Provide a sample input histopathology image.  

```markdown
![Input Image](inputs/sample_input.jpg)
```
## Output Example

The CNN predicts whether the tissue is cancerous or normal. Grad-CAM highlights important regions in the image.

![Output Image](outputs/sample_output.jpg)
**Prediction Example:**

**Input:** Lung tissue image

**Model Prediction:** Cancerous

**Confidence:** 96%

## How to Run

**Clone the repository:**

- git clone <your-repo-link>

**Install dependencies:**

- pip install -r requirements.txt
- Preprocess dataset (resizing, normalization, augmentation).

**Train the CNN model:**

- Open code.ipynb and run all cells

**Evaluate model on test data:**

- Outputs confusion_matrix.png and performance.png

**Generate Grad-CAM visualizations:**

- Saved automatically in outputs folder
- Test new images using test.ipynb.

## Results

- Achieved high accuracy in classifying lung cancer histopathology images

- Confusion matrix visualizes classification performance across Normal, ACA, and SCC classes

- Performance metrics image shows Precision, Recall, and F1 Score

- Grad-CAM visualizations provide explainable insights, highlighting cancerous regions

- Supports faster and more reliable decision-making for medical practitioners

## Future Work

- Extend to multi-class classification for different cancer types

- Integrate with clinical workflows for real-time diagnosis

- Experiment with transfer learning using pre-trained models like ResNet or EfficientNet

- Improve interpretability using other XAI techniques

## Author
**Kabilan Karthikeyan**  
- Data Analyst aspiring to grow in the Data Science field 
