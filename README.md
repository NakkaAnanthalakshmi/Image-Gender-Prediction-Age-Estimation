# Image-Gender-Prediction-Age-Estimation

A computer vision project that predicts **gender** and **age** from human face images using **OpenCV** and **deep learning** models.

## 📌 Overview

This project uses pre-trained deep learning models and OpenCV to:
- Detect faces in images or video streams.
- Predict the **age range** of each detected face.
- Predict the **gender** (Male/Female) of the face.

It serves as a great starting point for facial analytics applications like smart advertising, personalized user experiences, and demographic analysis.

---

## 💡 Features

- 🎯 Real-time face detection and prediction.
- 🧠 Deep learning-based gender and age classification.
- 🖼️ Works on both images and live webcam feeds.
- 📦 Lightweight and easy to run with OpenCV and a few deep learning models.

---

## 🧰 Tech Stack

- Python
- OpenCV
- Pre-trained Caffe models
- NumPy

---

## 📁 Project Structure
- Image-Gender-Prediction-Age-Estimation/
- │
- ├── age_deploy.prototxt
- ├── age_net.caffemodel
- ├── gender_deploy.prototxt
- ├── gender_net.caffemodel
- ├── example_image.jpg
- ├── predict.py
- └── README.md

---

## 🧪 Age Groups Predicted

| Label Index | Age Range    |
|-------------|--------------|
| 0           | (0-2)        |
| 1           | (4-6)        |
| 2           | (8-12)       |
| 3           | (15-20)      |
| 4           | (25-32)      |
| 5           | (38-43)      |
| 6           | (48-53)      |
| 7           | (60-100)     |

---

## 👩‍💻 How to Run

### 1. Clone the repository
- git clone https://github.com/NakkaAnanthalakshmi/Image-Gender-Prediction-Age-Estimation.git
- cd Image-Gender-Prediction-Age-Estimation
### 2. Install dependencies
- pip install opencv-python numpy
### 3. Run the script
- python predict.py
- Make sure your webcam is accessible or replace with image/video input accordingly.

### 📸 Sample Output
- Gender: Male
- Age: (25-32)
- Real-time bounding box with predictions over detected face.
- 📌 Notes
- This uses pre-trained Caffe models (.caffemodel) available online.
- Accuracy is approximate — intended for demonstration/education only.

