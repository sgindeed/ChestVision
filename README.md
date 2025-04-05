
# 🩻 ChestVision – AI-Powered Chest X-Ray Classifier

> Classify Chest X-rays into COVID-19, Lung Opacity, Normal, and Viral Pneumonia using Deep Learning, now lightning-fast with **TensorFlow Lite**! ⚡

![Made with love](https://img.shields.io/badge/Made%20with-%E2%9D%A4%EF%B8%8F%20and%20TFLite-blueviolet)
![FastAPI](https://img.shields.io/badge/Backend-FastAPI-%23009688)
![React](https://img.shields.io/badge/Frontend-React-blue)
![Vercel](https://img.shields.io/badge/Deployed%20on-Vercel-black)
![Render](https://img.shields.io/badge/API%20on-Render-%2300c7b7)

---

## 🌐 Live Demo

🔵 **Frontend**: [chestvision.vercel.app](https://chestvision.vercel.app)  
🧠 **API**: [chestvision-api.onrender.com/predict](https://chestvision-api.onrender.com/predict)

---

## 📸 What is ChestVision?

ChestVision is a web app that lets you **upload chest X-rays** and get **instant disease prediction** using a deep learning model trained on real radiology data.

It classifies images into:
- 🦠 **COVID-19**  
- ☁️ **Lung Opacity**  
- ✅ **Normal**  
- 🧬 **Viral Pneumonia**

Built with 🐍 FastAPI + ⚛️ React + 🧠 TensorFlow Lite for blazing fast predictions 🚀

---

## ⚙️ Tech Stack

| Tech         | Purpose                          |
|--------------|----------------------------------|
| 🐍 Python     | Backend API with FastAPI         |
| ⚡ TFLite      | Lightweight, fast image prediction |
| ⚛️ React.js    | Frontend interface               |
| 🎨 CSS        | Stylish UI (dark + blue theme)   |
| ☁️ Render     | Backend Hosting                  |
| ⚡ Vercel     | Frontend Hosting                 |

---

## 🗂️ Folder Structure

```
ChestVision/
├── api.py                         # FastAPI app with TFLite model
├── covid19_vgg16_combined.tflite # TFLite model file
├── requirements.txt              # Python dependencies
├── Procfile                      # For Render deployment
├── frontend/                     # React frontend
│   ├── public/
│   └── src/
└── README.md                     # This file 😉
```

---

## 🚀 Getting Started

### 🔧 Backend (FastAPI + TFLite)

```bash
git clone https://github.com/sgindeed/ChestVision.git
cd ChestVision
pip install -r requirements.txt
python api.py
```

> Make sure `covid19_vgg16_combined.tflite` is present in the root directory.

---

### 💻 Frontend (React)

```bash
cd frontend
npm install
npm start
```

> App will run locally at `http://localhost:3000`, calling backend on port `8000`.

---

## 🌟 Features

✨ Upload Chest X-ray images  
🧠 Instant classification with TFLite  
📱 Fully responsive & mobile-ready  
🖤 Modern UI with dark-blue theme  
🚀 Hosted & production-ready

---

## 🧠 Model Info

- Architecture: **VGG16**
- Converted to: **TensorFlow Lite (.tflite)**
- Classes:
  - COVID-19
  - Lung Opacity
  - Normal
  - Viral Pneumonia

---

## 💌 Credits

Made with ❤️ and ⚡ by [**Supratim**](https://github.com/sgindeed)

[![GitHub](https://img.shields.io/badge/GitHub-sgindeed-181717?style=for-the-badge&logo=github)](https://github.com/sgindeed)

---

## 🌈 Support

If you find this helpful, leave a ⭐ on [GitHub](https://github.com/sgindeed/ChestVision)  
and share
```
