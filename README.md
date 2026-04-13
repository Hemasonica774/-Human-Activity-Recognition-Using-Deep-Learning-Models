# 🚀 Human Activity Recognition Using Deep Learning Models

## 📌 Project Overview
This project focuses on **Human Activity Recognition (HAR)** using deep learning techniques to automatically identify human actions from video data. The system leverages advanced models to analyze both spatial and temporal features, enabling accurate and real-time activity classification.

---

## 🎯 Objective
- To develop an intelligent system that recognizes human activities from videos  
- To achieve high accuracy (>90%) with low computational cost  
- To enable real-time prediction for practical applications  

---

## 🧠 Technologies Used
- Python  
- TensorFlow / Keras  
- OpenCV  
- Deep Learning (CNN, 3D CNN)  
- MoViNet (Mobile Video Network)  
- MoveNet (Pose Estimation)  

---

## ⚙️ System Workflow
1. **Video Input** – User uploads a video  
2. **Frame Extraction** – Video converted into frames  
3. **Preprocessing** – Resize and normalize frames  
4. **Pose Detection** – Extract keypoints using MoveNet  
5. **Model Processing** – MoViNet analyzes temporal + spatial features  
6. **Prediction** – Activity label + confidence score displayed  

---

## 🏗️ Model Details
- Uses **MoViNet-A0** for efficient video classification  
- Captures **spatiotemporal features** using 3D convolutions  
- Lightweight and suitable for real-time applications  

---

## 📊 Dataset
- UCF101 Dataset (subset used)  
- Activities include:
  - Walking  
  - Running  
  - Sitting  
  - Standing  
  - Jumping  

---

## 📈 Results
- Achieved **~92% accuracy**  
- High precision and recall across activity classes  
- Real-time prediction with low latency  

---

## 💡 Applications
- 🎥 Video Surveillance  
- 🏥 Healthcare Monitoring  
- 🏠 Smart Homes  
- 🏃 Sports Analysis  
- 🏭 Industrial Safety  
- 🤖 Human-Computer Interaction  

---

## 🧪 Testing
- Black Box Testing  
- White Box Testing  
- All test cases passed successfully ✅  

---

## 📌 Features
- Real-time activity recognition  
- Pose-based detection (robust to background noise)  
- Lightweight and scalable  
- Web-based interface for easy use  

---

## 🔮 Future Enhancements
- Add more activity classes and datasets  
- Integrate LSTM / Transformer models  
- Deploy on mobile & edge devices  
- Real-time alert system for abnormal activities  

---

## 🖥️ How to Run

```bash
# Install dependencies
pip install -r requirements.txt

# Run the application
python app.py
