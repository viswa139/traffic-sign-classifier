# Traffic Sign Classification System

## 📌 Overview
A deep learning–based real-time traffic sign recognition system built using TensorFlow and OpenCV.  
This project classifies over 40 traffic signs using a CNN model and provides fast inference for real-time deployment.

---

## 🧰 Tech Stack
- Python
- TensorFlow
- OpenCV
- NumPy
- Flask (optional for deployment)
- Raspberry Pi (optional hardware extension)

---

## 🚀 Features
- CNN-based classifier for 40+ traffic classes  
- Real-time image processing with OpenCV  
- Data augmentation and regularization for improved accuracy  
- Model pruning and quantization for faster inference  
- Exportable model for embedded deployment  

---

## 📊 Model Performance
- **Accuracy:** 92% on test dataset  
- **Speed Improvement:** 30% faster inference using pruning & quantization  
- **Training Enhancements:** Data augmentation, dropout, and learning rate scheduling  

---

## 🔧 How to Run
1. Clone the repository  
2. Install dependencies  
3. Run the classifier  

---

## 📂 Project Structure
├── model/ # Trained CNN model files
├── static/ # Images / CSS files for UI (if using Flask)
├── app.py # Main script for prediction
├── requirements.txt # Dependencies
└── README.md # Project documentation

## ✨ Future Improvements
- Deploy on Raspberry Pi for edge detection  
- Improve accuracy with EfficientNet / MobileNet  
- Build a web dashboard for live detection  
- Add bounding-box detection 
