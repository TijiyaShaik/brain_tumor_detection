# 🧠 Brain Tumor Detection Using Deep Learning

## 📌 Project Overview

Brain Tumor Detection is a deep learning-based image classification project designed to detect and classify brain tumors from MRI (Magnetic Resonance Imaging) scans.

The project uses a **Convolutional Neural Network (CNN)** to analyze MRI images and classify them into four categories: Glioma, Meningioma, Pituitary Tumor, and No Tumor.

A web-based application is developed using **Flask**, allowing users to upload MRI images and obtain predictions along with confidence scores through an interactive interface.

The trained model achieved approximately **95% accuracy** during evaluation.

---

## 🎯 Project Objectives

* Develop a deep learning model for brain tumor detection using MRI images.
* Apply image preprocessing techniques to prepare MRI scans for classification.
* Implement a CNN-based image classification approach.
* Train and evaluate the deep learning model.
* Develop a user-friendly web application using Flask.
* Generate predictions based on uploaded MRI images.
* Classify MRI images into four different categories.

---

## 🛠️ Technologies Used

| Technology | Purpose                            |
| ---------- | ---------------------------------- |
| Python     | Core programming language          |
| TensorFlow | Deep learning framework            |
| Keras      | CNN model development and training |
| OpenCV     | Image processing                   |
| NumPy      | Numerical computations             |
| Flask      | Web application development        |
| HTML       | Frontend structure                 |
| CSS        | Frontend styling                   |
| VS Code    | Development environment            |

---

## 🧠 Model Development

The project uses a **Convolutional Neural Network (CNN)** for processing and analyzing brain MRI images.

### Classification Categories

The trained model identifies the following four categories:

| Category        | Description                                                                  |
| --------------- | ---------------------------------------------------------------------------- |
| Glioma          | A type of tumor that originates in glial cells of the brain.                 |
| Meningioma      | A tumor that develops in the meninges surrounding the brain and spinal cord. |
| Pituitary Tumor | A tumor that develops in the pituitary gland.                                |
| No Tumor        | MRI images classified as not showing a tumor by the model.                   |

### Model Development Workflow

1. **Dataset Collection:** Collected brain MRI images for model development.
2. **Image Preprocessing:** Resized and processed MRI images for model input.
3. **Model Development:** Developed a CNN architecture using TensorFlow and Keras.
4. **Model Training:** Trained the model using the prepared MRI image dataset.
5. **Model Evaluation:** Evaluated the trained model using appropriate performance metrics.
6. **Model Saving:** Saved the trained model in `.h5` format.
7. **Prediction:** Used the trained model to classify uploaded MRI images.

### Model Performance

| Metric                  | Result                             |
| ----------------------- | ---------------------------------- |
| Model Architecture      | Convolutional Neural Network (CNN) |
| Accuracy                | Approximately 95%                  |
| Deep Learning Framework | TensorFlow                         |
| Model API               | Keras                              |
| Model Format            | H5                                 |

---

## ⚙️ Application Features

* Upload brain MRI images through a web interface.
* Process uploaded MRI images for prediction.
* Classify MRI images into four categories.
* Display the predicted tumor category.
* Display the model's prediction confidence score.
* Preview the uploaded MRI image.
* Simple and user-friendly interface.

---

## 📸 Application Output Screenshots

The application provides predictions for four different MRI image categories. The following screenshots demonstrate the model's classification results and confidence scores.

### 1. Meningioma Tumor Detection

<img width="1188" height="895" alt="Screenshot 2026-11-01 114328" src="https://github.com/user-attachments/assets/4778ea66-cc6e-4ed4-bdbd-b25b1f7afecb" />


### 2. No Tumor Detection

<img width="1920" height="1022" alt="Screenshot 2026-11-01 114436" src="https://github.com/user-attachments/assets/fe3387ab-d7e8-4048-8c60-dd457f3dbd0b" />


### 3. Pituitary Tumor Detection

<img width="1920" height="1022" alt="Screenshot 2026-11-01 114632" src="https://github.com/user-attachments/assets/4cbac5f4-77ca-4430-aa20-34afd705fc16" />


### 4. Glioma Tumor Detection

<img width="1920" height="1022" alt="Screenshot 2026-11-01 114718" src="https://github.com/user-attachments/assets/7dbc8740-2b51-4d5d-8336-f130c76fa099" />


---

## 📂 Project Structure

```text
brain_tumor_detection/
│
├── models/
│   ├── Brain_Tumor.ipynb
│   
│
├── sample_MRI_Images/
│   ├── Te-gl_0015.jpg
│   ├── Te-meTr_0001.jpg
│   ├── Te-noTr_0004.jpg
│   └── Te-piTr_0003.jpg
│
├── templates/
│   └── index.html
│
├── output_screenshots/
│   ├── meningioma.png
│   ├── no_tumor.png
│   ├── pituitary.png
│   └── glioma.png
│
├── uploads/
│
├── .gitignore
│
├── main.py
│
└── README.md
```

---

## 🚀 Installation and Execution

Follow these steps to run the project locally.

### 1. Clone the Repository

```bash
git clone https://github.com/TijiyaShaik/brain_tumor_detection.git
```

### 2. Navigate to the Project Directory

```bash
cd brain_tumor_detection
```

### 3. Install Required Dependencies

```bash
pip install tensorflow keras flask opencv-python numpy pillow
```

### 4. Run the Flask Application

```bash
python main.py
```

### 5. Access the Application

Open your web browser and navigate to:

```text
http://127.0.0.1:5000/
```

Upload a brain MRI image and click the **Upload and Detect** button to view the prediction result.

---

## 🔮 Future Enhancements

* Improve model performance using advanced CNN architectures.
* Explore transfer learning techniques.
* Incorporate additional evaluation metrics such as precision, recall, and F1-score.
* Enhance the user interface and prediction visualization.
* Deploy the application for wider accessibility.

---

## 📌 Conclusion

The Brain Tumor Detection project demonstrates the application of deep learning and computer vision techniques in medical image analysis.

By combining CNN-based image classification, TensorFlow, Keras, OpenCV, and Flask, this project provides an interactive approach to analyzing brain MRI images and classifying them into four categories.

This project strengthened practical knowledge of **Deep Learning, CNN, Image Processing, Model Training, and Web Application Development**.

---

**Project Category:** Deep Learning | Computer Vision | Healthcare AI

**Development Environment:** Visual Studio Code

**Technologies:** Python, TensorFlow, Keras, OpenCV, Flask, HTML, CSS

**Author:** Tijiya Bhanu
