# 🌾 Rice Plant Disease Detection Using Deep Learning

## 📌 Project Overview

This project is a **Deep Learning-based Rice Plant Disease Detection System** developed using **TensorFlow, Keras, MobileNetV2, OpenCV, and Streamlit**. The system automatically detects diseases from rice leaf images and classifies them into one of three categories.

The application helps identify rice plant diseases quickly, reducing the need for manual inspection and supporting early disease management.

---

## 🎯 Objectives

* Detect rice leaf diseases using Deep Learning.
* Classify rice leaf images into different disease categories.
* Build an easy-to-use Streamlit web application.
* Provide fast and accurate predictions.

---

## 🌱 Diseases Detected

* Bacterial Leaf Blight
* Brown Spot
* Leaf Smut

---

## 🧠 Model Used

* Transfer Learning
* **MobileNetV2 (Pre-trained on ImageNet)**
* TensorFlow / Keras

---

## 📂 Dataset

The dataset contains images of rice leaves belonging to three disease classes:

* Bacterial Blight
* Brown Spot
* Leaf Smut

The images are preprocessed, resized to **224 × 224**, normalized, and augmented before training.

---

## ⚙️ Data Preprocessing

The following preprocessing techniques were applied:

* Image Resizing (224 × 224)
* Pixel Normalization
* Data Augmentation

  * Rotation
  * Zoom
  * Horizontal Flip
  * Width Shift
  * Height Shift
  * Shear Transformation

Dataset Split:

* Training: **80%**
* Validation: **20%**

---

## 🚀 Technologies Used

* Python
* TensorFlow
* Keras
* MobileNetV2
* OpenCV
* NumPy
* Matplotlib
* Streamlit
* Google Colab

---

## 📊 Model Performance

| Metric              | Value                    |
| ------------------- | ------------------------ |
| Validation Accuracy | **96.23%**               |
| Loss Function       | Categorical Crossentropy |
| Optimizer           | Adam                     |

---

## 💻 Web Application

The project includes a Streamlit web application where users can:

* Upload a rice leaf image
* Predict the disease
* View prediction confidence
* Display confidence distribution
* Receive disease information

---

## 📁 Project Structure

```text
Rice-Plant-Disease-Detection/
│── Rice_Project.ipynb
│── app.py
│── rice_disease_model.h5
│── requirements.txt
│── README.md
```

---

## ▶️ Installation

Clone the repository:

```bash
git clone https://github.com/SohailAkhtar466/Rice-Plant-Disease-Detection.git
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Run the Streamlit application:

```bash
streamlit run app.py
```

---

## 📸 Output

Add screenshots here after uploading them.


* Home Page
* <img width="1339" height="581" alt="page1" src="https://github.com/user-attachments/assets/cf946053-5b74-45d4-9dc8-19b52d7a64cc" />

* Prediction Result
* Confidence Graph

---

## 📈 Future Improvements

* Detect additional rice diseases.
* Deploy the application on Streamlit Cloud.
* Improve prediction speed.
* Add treatment and prevention recommendations.
* Support real-time camera detection.

---

## 👨‍💻 Author

**Sohail Akhtar**

GitHub:
https://github.com/SohailAkhtar466

---

## ⭐ Acknowledgements

This project was developed as a Machine Learning / Deep Learning project using TensorFlow, Keras, MobileNetV2, OpenCV, and Streamlit. Transfer learning with MobileNetV2 provides an efficient and lightweight approach for image classification tasks, making it well suited for web deployment.
