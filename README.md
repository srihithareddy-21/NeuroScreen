# NeuroScreen  
Deep Learning-Based Multimodal Analysis for Early Mental Health Detection

---

## 📌 Project Overview
NeuroScreen is a deep learning–based mental health screening system designed for the early detection of mental health disorders using multimodal analysis. The project combines speech signal processing and behavioural data analysis using the MODMA dataset to identify subtle early indicators of mental health conditions.

---

## ❗ Problem Statement
Mental illness affects millions of people worldwide, yet early diagnosis remains difficult due to:
- Social stigma
- Lack of accessible diagnostic tools
- Subjective manual assessments
- Difficulty detecting subtle behavioural and vocal changes

Traditional machine learning approaches often fail to capture the temporal nature of speech signals and require extensive manual preprocessing.

---

## 💡 Proposed Solution
NeuroScreen introduces a hybrid deep learning architecture that combines:
- **CNN (Convolutional Neural Network)** for spatial feature extraction
- **BiLSTM (Bidirectional Long Short-Term Memory)** for temporal speech pattern analysis

The system performs multimodal fusion of:
- Vocal biomarkers
- Behavioural questionnaire data

to generate:
- Confidence scores
- Risk categorization (Low / Moderate / High)

---

## ✨ Key Features
- 🎤 Speech-based mental health analysis
- 🧠 Behavioural data integration
- 📊 CNN + BiLSTM hybrid architecture
- ⚡ FastAPI backend for real-time processing
- 🌐 Interactive web-based frontend
- 📈 Confidence score and risk prediction
- 🔍 Multimodal late fusion mechanism

---

## 🛠️ Technologies Used
- Python
- FastAPI
- Deep Learning
- CNN
- BiLSTM
- HTML
- CSS
- JavaScript
- Jupyter Notebook
- Machine Learning
- Data Processing

---

## 📂 Dataset
This project uses the **MODMA (Multimodal Open Dataset for Mental Disorder Analysis)** dataset, which contains:
- Speech recordings
- Behavioural information
- Mental health research data

The dataset is used for extracting acoustic and behavioural features related to depression and other mental health conditions.

---

## 🏗️ System Architecture
The proposed architecture includes:
1. Audio preprocessing
2. Feature extraction (MFCC and acoustic features)
3. CNN-based spatial analysis
4. BiLSTM temporal learning
5. Behavioural data fusion
6. Risk prediction and confidence scoring

---

## 📊 Results
- ✅ **95.2% Accuracy**
- ✅ **94.5% Precision**
- ✅ **93.8% Sensitivity**
- ✅ **0.97 AUC-ROC**

The model effectively captures:
- Speech rhythm variations
- Monotone pitch
- Delayed speech patterns
- Behavioural indicators

---

## ⚠️ Existing System Limitations
Traditional approaches using:
- SVM
- KNN
- LightGBM

suffer from:
- High preprocessing complexity
- Poor temporal understanding
- Heavy deployment requirements
- Lower real-time efficiency

---

## 🚀 Future Work
- Improve model generalization
- Integrate EEG signal analysis
- Add facial emotion recognition
- Implement Explainable AI (XAI)
- Deploy on edge devices for real-time monitoring

---

## ▶️ How to Run the Project

### Backend
```bash
uvicorn main:app --reload
```

### Frontend
Open:
```text
frontend/index.html
```

in your browser.

---

## 👥 Team Members
- B. Sathvika
- E. Sree Charani
- I. Srihitha
- MD. Sameera
- T. Jhasmitha

### 🎓 Mentor
Dr. M Deepika

## 📄 License
This project is developed for academic and research purposes.
