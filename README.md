# 🎙️ Speech Emotion Recognition (SER)

A deep learning project that classifies speech into **8 emotions** using the RAVDESS dataset.

## 📌 Overview
| | |
|---|---|
| **Dataset** | RAVDESS — 1440 `.wav` files, 24 actors |
| **Features** | MFCC (40) + Chroma (12) + Mel Spectrogram (128) |
| **Model** | LSTM → Dense → Softmax |
| **Emotions** | neutral, calm, happy, sad, angry, fear, disgust, surprised |

## 🚀 How to Run
1. Open the notebook in [Google Colab](https://colab.research.google.com/)
2. Click **Runtime → Run all**
3. Upload your `Audio_Speech_Actors_01-24.zip` when prompted

## 📦 Requirements
librosa, tensorflow, scikit-learn, matplotlib, seaborn

## 📁 Dataset
Download RAVDESS from [Zenodo](https://zenodo.org/record/1188976)
