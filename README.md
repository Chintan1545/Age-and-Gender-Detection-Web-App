# 📌 Age and Gender Detection Web App

A Deep Learning based **Age and Gender Detection System** built using **OpenCV DNN** and deployed with **Streamlit**.

This application detects faces from an uploaded image and predicts:

* 👤 Gender (Male/Female)
* 🎂 Age Group (0–100 years range categories)

---

## 🚀 Technologies Used

* 🐍 Python
* 🎥 OpenCV (DNN Module)
* 🌐 Streamlit
* 🔢 NumPy

---

## 🧠 Deep Learning Models Used

This project uses pre-trained CNN models:

* Face Detection Model (`opencv_face_detector_uint8.pb`)
* Age Detection Model (`age_net.caffemodel`)
* Gender Detection Model (`gender_net.caffemodel`)

These models are loaded using OpenCV's DNN module.

---

## 📂 Project Structure

```
age-gender-detection/
│
├── app.py
├── opencv_face_detector.pbtxt
├── opencv_face_detector_uint8.pb
├── age_deploy.prototxt
├── age_net.caffemodel
├── gender_deploy.prototxt
├── gender_net.caffemodel
├── requirements.txt
└── README.md
```

---

## ⚙ Installation

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/Chintan1545/age-gender-detection.git
cd age-gender-detection
```

### 2️⃣ Create Conda Environment (Optional)

```bash
conda create -p myenv python=3.9
conda activate myenv
```

### 3️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

---

## ▶ Run the Application

```bash
streamlit run app.py
```

The app will open in your browser:

```
http://localhost:8501
```

---

## 🖼 How It Works

1. User uploads an image
2. Face detection model detects faces
3. Detected face is passed to:

   * Gender prediction model
   * Age prediction model
4. Results are displayed on the image

---

## 📊 Age Categories

```
(0-2)
(4-6)
(8-12)
(15-20)
(25-32)
(38-43)
(48-53)
(60-100)
```

---

## 📌 Future Improvements

* Live Webcam Support
* Deployment on Streamlit Cloud
* Real-time Video Processing
* Accuracy Optimization

---

## 👨‍💻 Author

MCA (AI & ML) Student
AI/ML & Generative AI Enthusiast
