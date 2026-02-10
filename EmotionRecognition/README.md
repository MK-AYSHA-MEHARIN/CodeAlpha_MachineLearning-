# 🎙️ Speech Emotion Recognition using RAVDESS

This project focuses on predicting human emotions from speech audio using machine learning techniques.  
The RAVDESS (Ryerson Audio-Visual Database of Emotional Speech and Song) dataset is used for training and evaluation.

---

## 📌 Objective
To build a classification model that can recognize emotions such as **happy, sad, angry, calm, fearful, disgust, and surprised** from voice recordings.

---

## 📂 Dataset## 

This project uses the **RAVDESS Emotional Speech Audio** dataset.

Due to file size limitations, the dataset is not uploaded to this repository.

You can download it from Kaggle:
👉 https://www.kaggle.com/datasets/uwrfkaggler/ravdess-emotional-speech-audio

**RAVDESS Emotional Speech Audio**

- 24 professional actors (12 male, 12 female)
- Speech recorded with different emotions and intensities
- Audio format: `.wav`
- Total files: 1440

Dataset structure example:

audio_speech_actors_01-24/
Actor_01/
03-01-01-01-01-01-01.wav


---

## ⚙️ Technologies Used
- Python
- Google Colab
- NumPy
- Librosa (audio processing)
- Scikit-learn
- Pandas

---

## 🧠 Methodology

1. Load audio files  
2. Extract features (MFCC)  
3. Generate emotion labels from filenames  
4. Split into training & testing sets  
5. Train ML model  
6. Evaluate performance

---

## 🎵 Feature Extraction
Mel Frequency Cepstral Coefficients (**MFCC**) are extracted from each audio file to represent speech characteristics numerically.

---

## 🤖 Models Used
- Logistic Regression  
- Random Forest (can be extended)  
- Decision Tree (optional)

---

## 📊 Evaluation Metrics
- Accuracy  
- Precision  
- Recall  
- F1-score  

---

## ✅ Results
The model successfully classifies emotions from unseen speech samples with good accuracy.  
(You can insert your accuracy here, e.g., **78%**).

---

## 🚀 How to Run

1. Upload the dataset zip to Google Drive  
2. Mount Drive in Colab  
3. Unzip the dataset  
4. Run all notebook cells  

---

## 📁 Project Structure
```

├── emotion_recognition.ipynb
├── README.md
└── dataset (RAVDESS)
