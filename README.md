## 🧑‍🤝‍🧑 Face Swap using OpenCV and Dlib

This project demonstrates a **face swapping pipeline** using Python, OpenCV, and Dlib. It extracts facial landmarks from source and destination images using a pre-trained model (`shape_predictor_68_face_landmarks.dat`), performs Delaunay triangulation, and warps one face onto another using affine transformations.

### 🔍 Key Features

* Face detection and landmark extraction with Dlib
* Image warping using triangulation for realistic blending
* Seamless cloning for smooth face integration
* End-to-end implementation in Google Colab

### 📌 What Makes It Interesting

* Uses **pretrained facial landmark model** for accurate localization
* Demonstrates **real-time face alignment and swapping**
* Practical application of image processing and computer vision techniques

### 📁 Folder Contents

* `face_swap.ipynb` – Full implementation of the face swap logic with step-by-step code and visual output
* Dependencies: OpenCV, Dlib, NumPy

### 💡 Use Cases

* Fun face-swap applications
* Building blocks for deepfake engines or AR filters
* Educational tool for learning image processing techniques

