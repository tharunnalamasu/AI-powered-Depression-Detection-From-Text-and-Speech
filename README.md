# 🧠 AI-Powered Depression Detection from Text and Speech

A published research project that detects signs of depression from **typed text** and **live speech input** using Natural Language Processing (NLP) and Machine Learning — providing real-time predictions with confidence scores.

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![NLP](https://img.shields.io/badge/NLP-TF--IDF-FF6F00?style=for-the-badge)
![Machine Learning](https://img.shields.io/badge/ML-Random%20Forest-228B22?style=for-the-badge)
![Speech](https://img.shields.io/badge/Speech-Google%20Web%20Speech%20API-4285F4?style=for-the-badge&logo=google&logoColor=white)
![Status](https://img.shields.io/badge/Status-Published%20Paper-success?style=for-the-badge)

---

## 📄 Published Research

> **Paper Title:** AI-Powered Depression Detection from Text and Speech  
> **Published:** June 2025  
> **Domain:** Artificial Intelligence / Natural Language Processing  
> **Author:** Tharun Nalamasu

---

## 📌 About the Project

Mental health issues like depression often go undetected due to stigma and lack of access to professional help. This project addresses that gap by building an AI-powered screening tool that analyzes both **written text** and **live spoken words** to detect early signs of depression — instantly and privately.

> ⚠️ **Disclaimer:** This tool is for research and screening purposes only. It is **not** a substitute for professional medical diagnosis.

---

## ✨ Features

- 📝 **Text Analysis** — Paste or type any text to get an instant depression likelihood score
- 🎙️ **Live Speech Input** — Speak directly into the microphone; speech is transcribed and analyzed in real time
- 📊 **Confidence Scores** — Every prediction comes with a confidence percentage
- 🔄 **Real-time Processing** — Instant results with no delay
- 🤲 **Hands-free Mode** — Full speech-to-text for accessible mental health screening
- 🧪 **Dual-mode Detection** — Works on both text and audio input independently

---

## 🛠️ Tech Stack

| Component | Technology |
|-----------|------------|
| Language | Python |
| NLP Feature Extraction | TF-IDF (Term Frequency–Inverse Document Frequency) |
| ML Classifier | Random Forest |
| Speech Recognition | Google Web Speech API |
| Text Processing | NLTK / Scikit-learn |
| UI | Flask / Streamlit *(update as applicable)* |

---

## 🧠 How It Works

```
User Input (Text or Speech)
        │
        ▼
┌─────────────────────┐        ┌──────────────────────────┐
│   Text Input Mode   │        │   Speech Input Mode      │
│  (typed by user)    │        │  (Google Web Speech API) │
└────────┬────────────┘        └────────────┬─────────────┘
         │                                  │
         └──────────────┬───────────────────┘
                        ▼
             Text Preprocessing
             (cleaning, tokenizing)
                        │
                        ▼
              TF-IDF Vectorization
                        │
                        ▼
           Random Forest Classifier
                        │
                        ▼
        Prediction + Confidence Score
        (Depressed / Not Depressed — xx%)
```

---

## 📊 Model Performance

| Metric | Score |
|--------|-------|
| Accuracy | *(add your value)* |
| Precision | *(add your value)* |
| Recall | *(add your value)* |
| F1 Score | *(add your value)* |

---

## 📁 Project Structure

```
depression-detection-nlp/
├── dataset/
│   └── depression_data.csv        # Training dataset
├── model/
│   ├── train_model.py             # Model training script
│   ├── tfidf_vectorizer.pkl       # Saved TF-IDF vectorizer
│   └── random_forest_model.pkl    # Saved trained model
├── speech/
│   └── speech_to_text.py          # Google Web Speech API integration
├── app/
│   ├── app.py                     # Main Flask/Streamlit app
│   └── templates/
│       └── index.html             # UI template
├── utils/
│   └── preprocess.py              # Text cleaning & preprocessing
├── requirements.txt
└── README.md
```

---

## 🚀 Getting Started

### Prerequisites
```bash
Python >= 3.8
pip
Microphone (for speech mode)
```

### Installation

```bash
# 1. Clone the repository
git clone https://github.com/tharunalamasu/depression-detection-nlp.git
cd depression-detection-nlp

# 2. Create virtual environment
python -m venv venv
source venv/bin/activate        # On Windows: venv\Scripts\activate

# 3. Install dependencies
pip install -r requirements.txt

# 4. Run the application
python app/app.py
```

### Requirements (`requirements.txt`)
```
scikit-learn
nltk
pandas
numpy
flask
SpeechRecognition
pyaudio
joblib
```

---



---

## 🔬 Research Highlights

- Combined **text and speech modalities** for more robust detection
- Used **TF-IDF** to extract meaningful linguistic patterns linked to depression
- **Random Forest** chosen for its high accuracy and interpretability
- **Google Web Speech API** enabled real-time, hands-free screening
- Designed to be lightweight and deployable without GPU

---

## 🙋‍♂️ Author

**Tharun Nalamasu**  
📧 tharunnalamasu@gmail.com  
🔗 [LinkedIn](https://linkedin.com/in/tharunnalamasu) · [GitHub](https://github.com/tharunalamasu)

---

## 📄 License

This project is intended for research and educational purposes only.

---

> 💚 *If this project helped you or inspired your work, please give it a ⭐ — it means a lot!*
