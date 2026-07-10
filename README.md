# 🎵 Gesture-Controlled Spotify Media Controller

A real-time computer vision application that allows users to control Spotify media playback using hand gestures captured through a webcam.

The project uses **OpenCV** for image processing, **Histogram of Oriented Gradients (HOG)** for feature extraction, and a **Support Vector Machine (SVM)** classifier for gesture recognition.

❌ not using **MediaPipe**

---

## 📌 Features

- 🎥 Real-time webcam-based hand gesture recognition
- ✋ Detects multiple hand gestures
- 🎵 Controls Spotify playback using gestures
- ⚡ Fast HOG feature extraction
- 🤖 Machine Learning using Support Vector Machine (SVM)
- 📓 End-to-end training and inference notebooks

---

## 🛠 Technologies Used

- Python
- OpenCV
- NumPy
- Scikit-learn
- Joblib
- HOG Feature Extraction
- Support Vector Machine (SVM)
- Jupyter Notebook

---

## 📂 Project Structure

```
gesture-controlled-spotify-media-controller/
│
├── notebooks/
│   ├── 01_Dataset_Preparation.ipynb
│   ├── 02_HOG_SVM_Training.ipynb
│   ├── 03_Real_Time_Gesture_Recognition.ipynb
│   └── 04_Gesture_Controlled_Spotify.ipynb
│
├── demo.mp4
├── requirements.txt
└── README.md
```

---

## 📊 Dataset

This project uses the **HG14 Hand Gesture Dataset**.

Dataset Link:

https://www.kaggle.com/datasets/gulerosman/hg14-handgesture14-dataset

The dataset is **not included** in this repository because of its large size.

---

## 🤖 Trained Model

The trained SVM model (`hand-gesture-recognition-model.sav`) is **not included** in this repository because it exceeds GitHub's recommended file size.

To generate the model:

1. Download the dataset.
2. Run:

```
02_HOG_SVM_Training.ipynb
```

This notebook will train the SVM classifier and generate the model file.

---

## 🚀 How to Run

### 1. Clone the repository

```bash
git clone https://github.com/navodsamarakoon/gesture-controlled-spotify-media-controller.git
```

### 2. Install dependencies

```bash
pip install -r requirements.txt
```

### 3. Download the dataset

Download the HG14 Hand Gesture Dataset from Kaggle and place it in the project directory.

### 4. Train the model

Run:

```
02_HOG_SVM_Training.ipynb
```

### 5. Start gesture recognition

Run:

```
04_Gesture_Controlled_Spotify.ipynb
```

---

## 🎬 Demo

The repository includes a demonstration video.

📁 **demo.mp4**

GitHub will automatically display a video player when you click the file.

---

## 📈 Machine Learning Pipeline

```
Webcam Frame
      │
      ▼
Hand Detection
      │
      ▼
ROI Extraction
      │
      ▼
Image Resize
      │
      ▼
HOG Feature Extraction
      │
      ▼
SVM Classification
      │
      ▼
Gesture Prediction
      │
      ▼
Spotify Media Control
```

---

## 📌 Future Improvements

- Deep Learning (CNN) based gesture recognition
- MediaPipe hand landmark detection
- More gesture classes
- Improved lighting robustness
- Cross-platform media control
- Higher prediction accuracy

---

## 👨‍💻 Author

**Navod Samarakoon**

Computer Engineering Undergraduate  
University of Ruhuna

GitHub:
https://github.com/navodsamarakoon

---

## ⭐ Support

If you found this project useful, consider giving it a ⭐ on GitHub.
