
## 🧠 Overview  
**Face Verification AI** is a deep learning–powered facial verification system built using a **Siamese Neural Network** architecture.  
It enables real-time face verification through webcam or image upload using **TensorFlow**, **Keras**, and **OpenCV**, all wrapped in a simple **Streamlit UI**.

---

## 🧩 Tech Stack  
| Category | Technology |
|-----------|-------------|
| Language | Python 🐍 |
| Framework | TensorFlow / Keras |
| Interface | Streamlit |
| Computer Vision | OpenCV |
| Model Type | Siamese Neural Network |
| Deployment | Local / Streamlit Cloud |

---

## ⚙️ Features  
✅ Face registration via webcam or image upload  
✅ Real-time face verification  
✅ Pretrained Siamese model integration  
✅ Lightweight Streamlit UI  
✅ Compatible with macOS (Apple Silicon optimized)  

---

## 🚀 Run Locally  

```bash
# Clone the repository
git clone https://github.com/TDevViper/face_verification_ai.git
cd face_verification_ai


# Create a virtual environment
python3 -m venv .venv
source .venv/bin/activate  # On Windows use `.venv\Scripts\activate`

# Install dependencies
pip install -r requirements.txt

# Run the app
streamlit run app.py
````

---

## 🧰 Directory Structure

```
face_verification_ai/
│
├── app.py                # Main Streamlit app
├── requirements.txt      # All dependencies
├── siamese_model.h5      # Pretrained Siamese model
├── application_data/     # User-registered faces
├── .streamlit/           # Streamlit config
└── README.md             # Project documentation
```

---

## 🎯 Future Upgrades (FRIDAY Integration Plan)

🔹 Integrate Face Verification with FRIDAY AI login system
🔹 Add voice verification for multi-modal identity recognition
🔹 Convert model to ONNX or CoreML for real-time performance
🔹 Deploy via FastAPI microservice for scalable backend

---

## 🧑‍💻 Author

**Arnav Yadav**
💼 Developer | AI Enthusiast | Creator of FRIDAY AI
🌐 GitHub: [TDevViper](https://github.com/TDevViper)

---

## 💡 Inspiration

This project is **inspired by [Nick Nochnack’s FaceIDApp](https://github.com/nicknochnack/FaceIDApp)**
and refactored for **macOS (M1/M2)** with performance, dependency, and UI improvements.

---

## 🏷️ License

This project is open-source and available under the **MIT License**.

---

## ⚡ Preview

![Face Verification Demo](https://github.com/nicknochnack/FaceIDApp/raw/main/demo.gif)

---

⭐ **If you like this project, give it a star!**
It’s a part of my ongoing **FRIDAY AI Ecosystem** — an intelligent assistant built from scratch 💥

```
