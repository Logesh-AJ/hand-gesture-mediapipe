# ✋ Hand Gesture Recognition using MediaPipe

Real-time hand gesture recognition system built using MediaPipe, featuring custom dataset creation, model training, and live inference for human-computer interaction.

---

## 🧠 Tech Stack

* Python
* MediaPipe
* OpenCV
* NumPy
* Scikit-learn

---

## 🏗️ Workflow

### 1. Dataset Creation

* Captured hand landmarks using MediaPipe
* Stored labeled gesture data for training

### 2. Model Training

* Extracted features from hand landmarks
* Trained a classification model using Scikit-learn
* Saved trained model as `.pkl` file

### 3. Real-Time Inference

* Live webcam input using OpenCV
* MediaPipe used for hand tracking
* Gesture prediction using trained model

### 4. Output

* Recognized gestures displayed in real-time

---

## 📸 Results

![Gesture Output](demo_images/Screenshot2026-03-31133024)

---

## 🎥 Demo

[Watch Demo Video](https://youtu.be/EAgwuLkFv_E)

---

## ⚡ How to Run

1. Clone the repository

```
git clone https://github.com/yourusername/hand-gesture-mediapipe.git
```

2. Navigate to the project folder

```
cd hand-gesture-mediapipe
```

3. Install dependencies

```
pip install -r requirements.txt
```

4. Run the application

```
python src/main.py
```

---

## ⚙️ System Requirements

* Python >= 3.8
* Webcam (for real-time gesture detection)
* OS: Windows / Linux / macOS

---

## 📦 Dependencies

* opencv-python
* mediapipe
* numpy
* scikit-learn

---

## 📁 Project Structure

```
hand-gesture-mediapipe/
 ├── src/
 │    ├── create_dataset.py
 │    ├── train_model.py
 │    └── main.py
 ├── models/
 │    └── gesture_model.pkl
 ├── demo_images/
 ├── demo_video/
 ├── README.md
 └── requirements.txt
```

---

## 🚧 Future Improvements

* Improve model accuracy with larger dataset
* Add more gesture classes
* Optimize performance for edge devices
* Integrate with IoT or robotics systems

---

## 👤 Author
**Logesh A J**
---
