# 🧠 Brain Tumor Detection Using Deep Learning

## 📌 Project Overview

Brain Tumor Detection is a deep learning-based image classification project designed to detect brain tumors from MRI (Magnetic Resonance Imaging) scans.

The project uses a **Convolutional Neural Network (CNN)** to analyze MRI images and identify patterns associated with brain tumors.

An interactive web application is developed using **Python and Streamlit**, allowing users to upload MRI images and obtain predictions through a user-friendly interface.

The developed model achieved approximately **95% accuracy** during evaluation.

---

## 🎯 Project Objectives

* Develop a deep learning model for brain tumor detection using MRI images.
* Apply image preprocessing techniques to prepare MRI scans for classification.
* Implement a CNN-based image classification approach.
* Train and evaluate the deep learning model.
* Develop an interactive web application for MRI image uploads.
* Generate predictions based on uploaded MRI images.

---

## 🛠️ Technologies Used

| Technology | Purpose                            |
| ---------- | ---------------------------------- |
| Python     | Core programming language          |
| TensorFlow | Deep learning framework            |
| Keras      | CNN model development and training |
| OpenCV     | Image processing                   |
| NumPy      | Numerical computations             |
| Streamlit  | Interactive web application        |
| VS Code    | Development environment            |

---

## 🧠 Model Development

The project uses a **Convolutional Neural Network (CNN)** for processing and analyzing brain MRI images.

### Workflow

1. **Dataset Collection:** Collected brain MRI images for model development.
2. **Image Preprocessing:** Prepared MRI images by resizing and processing them.
3. **Model Development:** Developed a CNN model using TensorFlow and Keras.
4. **Model Training:** Trained the model using the prepared MRI image dataset.
5. **Model Evaluation:** Evaluated the trained model to measure its performance.
6. **Prediction:** Used the trained model to classify uploaded MRI images.

### Model Performance

| Metric                  | Result                       |
| ----------------------- | ---------------------------- |
| Model Architecture      | Convolutional Neural Network |
| Accuracy                | Approximately 95%            |
| Deep Learning Framework | TensorFlow                   |
| Model API               | Keras                        |
| Application Framework   | Streamlit                    |

---

## ⚙️ Application Features

* Upload brain MRI images.
* Process uploaded images for prediction.
* Analyze MRI images using the trained CNN model.
* Display prediction results through an interactive interface.
* Simple and user-friendly application.

---

## 📂 Project Structure

```text
brain_tumor_detection/
│
├── models/
│   └── Brain_Tumor.ipynb
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
├── .gitignore
│
├── main.py
│
└── README.md
```

---

## 🚀 Installation and Execution

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
pip install tensorflow streamlit opencv-python numpy pillow
```

### 4. Run the Application

```bash
streamlit run main.py
```

### 5. Access the Application

Open the application in your browser using:

```text
http://localhost:8501
```

---

## 🔮 Future Enhancements

* Improve model performance using advanced CNN architectures.
* Explore transfer learning techniques.
* Incorporate additional evaluation metrics such as precision, recall, and F1-score.
* Improve the application interface and prediction visualization.
* Deploy the application for wider accessibility.

---


## 📌 Conclusion

The Brain Tumor Detection project demonstrates the application of deep learning and computer vision techniques in medical image analysis.

By combining CNN-based image classification, TensorFlow, Keras, OpenCV, and Streamlit, this project provides an interactive approach to analyzing brain MRI images.

This project strengthened practical knowledge of **Deep Learning, CNN, Image Processing, Model Training, and Web Application Development**.

---

**Project Category:** Deep Learning | Computer Vision | Healthcare AI

**Development Environment:** Visual Studio Code

**Technologies:** Python, TensorFlow, Keras, OpenCV, Streamlit

**Author:** Tijiya Bhanu
