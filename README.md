<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:36D1DC,100:5B86E5&height=250&section=header&text=Passport%20Photo%20Face%20Detection&fontSize=35&fontColor=ffffff&animation=fadeIn&fontAlignY=40" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.13-blue?logo=python" />
  <img src="https://img.shields.io/badge/OpenCV-Computer%20Vision-green?logo=opencv" />
  <img src="https://img.shields.io/badge/NumPy-Numerical%20Computing-blue?logo=numpy" />
  <img src="https://img.shields.io/badge/Matplotlib-Visualization-orange" />
  <img src="https://img.shields.io/badge/Haar%20Cascade-Face%20Detection-red" />
  <img src="https://img.shields.io/badge/Jupyter-Notebook-orange?logo=jupyter" />
  <img src="https://img.shields.io/badge/Status-Completed-success" />
</p>

---

# 📸 Passport Photo Face Detection using OpenCV

## 📖 Project Overview

This project demonstrates the fundamentals of **Computer Vision** using **OpenCV** and **Python**. The system processes a passport-size photograph and detects human faces using the **Haar Cascade Classifier**, a pre-trained face detection model provided by OpenCV.

The project also showcases several image processing techniques including:

- Image Loading
- Image Visualization
- Grayscale Conversion
- Image Resizing
- Image Rotation
- Image Annotation
- Gaussian Blur
- Edge Detection
- Face Detection

---

## 🚀 Features

✅ Load images using OpenCV

✅ Display images using Matplotlib

✅ Convert images to Grayscale

✅ Resize images for processing

✅ Rotate images

✅ Draw Rectangles, Circles, and Text

✅ Apply Gaussian Blur Filtering

✅ Perform Canny Edge Detection

✅ Detect Faces using Haar Cascade Classifier

✅ Display Bounding Boxes around detected faces

---

## 🛠️ Technologies Used

| Technology | Purpose |
|------------|----------|
| Python | Programming Language |
| OpenCV | Image Processing & Face Detection |
| NumPy | Numerical Operations |
| Matplotlib | Image Visualization |
| Jupyter Notebook | Interactive Development Environment |

---

## 📂 Project Structure

```text
Passport_Face_Detection/
│
├── Passport_Size_Face_Detection.ipynb
├── passport.jpg
├── README.md
└── requirements.txt
```

---

## ⚙️ Installation

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/Mehar-taj/Passport_Face_Detection.git
```

### 2️⃣ Navigate to the Project Folder

```bash
cd Passport_Face_Detection
```

### 3️⃣ Install Required Libraries

```bash
pip install -r requirements.txt
```

---

## 📦 Requirements

Create a file named `requirements.txt` and add:

```text
opencv-python
numpy
matplotlib
```

---

## ▶️ How to Run

1. Open the project folder in **VS Code**.
2. Open the Jupyter Notebook:

```text
Passport_Size_Face_Detection.ipynb
```

3. Place your passport image inside the project folder:

```text
passport.jpg
```

4. Run all notebook cells sequentially.

---

## 🔄 Project Workflow

```text
Passport Image
      │
      ▼
Image Loading
      │
      ▼
Image Visualization
      │
      ▼
Grayscale Conversion
      │
      ▼
Resize & Rotation
      │
      ▼
Image Annotation
      │
      ▼
Gaussian Blur
      │
      ▼
Edge Detection
      │
      ▼
Face Detection
      │
      ▼
Final Output
```

---

## 📚 Image Processing Techniques

### 1. Grayscale Conversion

Converts the color image into a single-channel grayscale image, reducing complexity and improving processing efficiency.

### 2. Image Resizing

Adjusts image dimensions to a fixed size for consistent processing.

### 3. Image Rotation

Rotates the image by 90° clockwise.

### 4. Image Annotation

Demonstrates image marking using:

- Rectangle
- Circle
- Text

### 5. Gaussian Blur

Smooths the image and reduces unwanted noise.

### 6. Canny Edge Detection

Detects object boundaries and significant image features.

### 7. Face Detection

Uses OpenCV's Haar Cascade Classifier to detect human faces and draw bounding boxes around them.

---

## 🧠 Face Detection Parameters

### scaleFactor = 1.1

Specifies how much the image size is reduced at each scale.

### minNeighbors = 5

Determines how many neighboring detections are required before a face is accepted.

### minSize = (30,30)

Defines the minimum face size that can be detected.

---

## 📊 Output

The system successfully:

- Loads the passport image
- Applies image transformations
- Performs image filtering
- Detects faces
- Draws bounding boxes around detected faces
- Displays the final annotated image

---

## 🎯 Key Learnings

Through this project, I gained practical experience in:

- Computer Vision Fundamentals
- OpenCV Image Processing
- Color Space Conversion
- Image Transformation
- Image Annotation
- Image Filtering
- Edge Detection
- Face Detection using Haar Cascade
- Data Visualization with Matplotlib

---

## 🔮 Future Improvements

- Real-Time Face Detection using Webcam
- Deep Learning-based Face Detection
- Face Recognition System
- Streamlit Web Application
- Multi-Face Tracking
- Automatic Passport Photo Validation

---

## 📸 Sample Output

### Original Passport Image

- Input image loaded from the project folder.

### Image Transformations

- Grayscale Image
- Resized Image
- Rotated Image

### Face Detection Output

- Face detected successfully.
- Bounding box drawn around detected face.

---

## 🤝 Connect With Me

<p align="center">
  <a href="https://github.com/Mehar-taj">
    <img src="https://img.shields.io/badge/GitHub-Mehar--taj-181717?style=for-the-badge&logo=github" />
  </a>
  
  <a href="https://www.linkedin.com/in/mehar-taj-a654102b6">
    <img src="https://img.shields.io/badge/LinkedIn-Mehar%20Taj-0A66C2?style=for-the-badge&logo=linkedin" />
  </a>
</p>

---

## ⭐ Support

If you found this project useful, please consider giving it a ⭐ on GitHub.

---

## 👨‍💻 Author

**Mehar Taj**

Aspiring Data Scientist | Machine Learning Enthusiast | Python Developer
