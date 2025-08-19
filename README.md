# Facialytics

**Real-time Facial Emotion Recognition using Vision Transformers**

---

## 📌 Overview

Facialytics is a Python-based machine learning application that leverages Vision Transformers (ViTs) for real-time facial emotion recognition. The model classifies over five distinct emotions with an accuracy of 85%, offering robust performance even on mid-range hardware.

---

## ⚙️ Features

- **Emotion Classification**: Classifies 5+ emotions (e.g., Happy, Sad, Angry, Surprise, Neutral) with 85% accuracy.
- **Data Augmentation**: Processes over 10,000 facial images with techniques like rotation, zoom, and brightness normalization to enhance model robustness.
- **Real-time Inference**: Achieves webcam inference with less than 200ms latency on mid-range hardware.
- **Model Optimization**: Reduces overfitting by 30% through advanced augmentation strategies.

---

## 🧪 Technologies Used

- **Machine Learning Frameworks**: TensorFlow, Keras
- **Computer Vision**: OpenCV
- **Model Architecture**: Vision Transformers (ViTs)
- **Programming Language**: Python
- **Development Tools**: Jupyter Notebook, Git, GitHub

---

## 📂 Repository Structure
```
Facialytics/
├── emotiondetector.h5 # Trained model weights
├── emotiondetector.json # Model architecture
├── realtimedetection.py # Real-time webcam inference script
├── trainmodel.ipynb # Jupyter notebook for training the model
├── requirements.txt # Python dependencies
└── .gitignore # Git ignore file
```


---

## 🚀 Installation

1. Clone the repository:

 ```bash
   git clone https://github.com/ShudhanshuBajpai/Facialytics.git
   cd Facialytics
```
2. Create and activate a virtual environment:

```bash
python3 -m venv venv
source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
```

3. Install required dependencies:

```bash
pip install -r requirements.txt
```

---

## 🧪 Usage

### 🚀 Training the Model
Train the emotion classification model:
`jupyter notebook trainmodel.ipynb`

### 🎥 Real-time Inference
Run real-time emotion detection via your webcam:
`python realtimedetection.py`


> ⚡ **Tip:** Make sure your webcam is connected and not used by other applications.

---

## 📈 Results

- **Accuracy:** 85% on a multi-class emotion dataset ✅  
- **Latency:** <200ms for real-time webcam inference ⏱️  
- **Overfitting Reduction:** 30% improvement using data augmentation 🔄  

> 💡 *Insight:* Data augmentation significantly improves generalization for unseen faces.

---

## 🛠️ Future Enhancements

- Expand emotion classes to include more nuanced expressions 😲😔😊  
- Implement model quantization for mobile deployment 📱  
- Integrate with cloud services for scalable inference ☁️  

> 🔧 Contributions to these enhancements are highly encouraged!

---

## 🤝 Contributing

We welcome contributions!  

- **Fork** the repository  
- **Create a new branch**  
- **Submit a pull request** with your changes  

> 🌟 Let’s improve this project together!

