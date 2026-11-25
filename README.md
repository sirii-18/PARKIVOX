# ParkiVox 🧠

Voice-Based Parkinson's Disease Prediction using Machine Learning.

## Overview

ParkiVox is an AI-powered voice analysis application designed to identify speech patterns associated with Parkinson's Disease. It uses audio processing and a Random Forest Machine Learning model to analyze voice recordings and generate predictions.

The project also includes a web interface for audio uploads and an AI-powered chatbot to provide information about Parkinson's Disease.

## About Parkinson's Disease

Parkinson's Disease is a progressive neurological disorder that affects movement, coordination, and speech. Changes in voice characteristics, such as pitch, jitter, and shimmer, can be associated with the condition.

ParkiVox explores voice analysis as a non-invasive approach to preliminary screening.

## How It Works

1. **Audio Recording:** Users record their voice or upload an existing audio file.
2. **Audio Processing:** The uploaded audio is processed and converted into a suitable format.
3. **Feature Extraction:** Acoustic features such as MFCC, jitter, shimmer, pitch, and Zero Crossing Rate are extracted.
4. **Classification:** A Random Forest Machine Learning model analyzes the extracted features.
5. **Results:** The application displays the prediction results.
6. **AI Chatbot:** Users can interact with a chatbot to learn about Parkinson's Disease.

## Features

- Voice recording and audio file uploading.
- Audio preprocessing and feature extraction.
- MFCC, jitter, shimmer, pitch, and other acoustic feature analysis.
- Random Forest-based classification.
- Prediction result visualization.
- Interactive chatbot for Parkinson's-related information.
- Google Gemini API integration.
- Feature analysis and graphical representations.

## Technologies Used

- **Programming Language:** Python
- **Machine Learning:** Scikit-learn, Random Forest
- **Audio Processing:** PyDub, FFmpeg
- **Data Processing:** NumPy, Pandas
- **Backend:** Flask
- **Frontend:** HTML, CSS, JavaScript
- **AI Integration:** Google Gemini API
- **Tools:** Git, GitHub, VS Code

## Installation

### Clone the Repository

```bash
git clone https://github.com/sirii-18/PARKIVOX.git
cd PARKIVOX
```

### Create a Virtual Environment

```bash
python -m venv venv
```

### Activate the Environment

**Windows:**
```bash
venv\Scripts\activate
```

**Linux / macOS:**
```bash
source venv/bin/activate
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Configure Environment Variables

Create a `.env` file and add your Google Gemini API key:

```env
API_KEY=your_google_gemini_api_key
```

### Run the Application

```bash
python app.py
```

Open the application in your browser:

`http://127.0.0.1:5000`

## Project Structure

```text
PARKIVOX/
│
├── app.py
├── app.js
├── index.html
├── style.css
│
├── feature_extraction.py
├── predict_audio.py
├── voice.py
├── voice_model.py
├── chatbot.py
├── generate_plots.py
│
├── voice.html
├── voice.css
├── voice.js
│
├── chatbot.html
├── chatbot.css
├── chatbot.js
│
├── result.html
├── result.css
│
├── parkinsons.data
├── full_set.csv
├── parkinson_model.pkl
├── scaler.pkl
│
├── requirements.txt
└── README.md
```

## Model

- **Algorithm:** Random Forest Classifier
- **Input:** Acoustic features extracted from voice recordings.
- **Output:** Voice-based classification prediction.
- **Model File:** `parkinson_model.pkl`
- **Scaler File:** `scaler.pkl`

## Future Enhancements

- Improve prediction performance using larger datasets.
- Explore deep learning models for voice classification.
- Add multilingual voice analysis.
- Improve real-time voice processing.
- Develop a mobile application.
- Enhance prediction visualization and model explainability.

## Disclaimer

ParkiVox is an educational and research-oriented project. It is not a certified medical diagnostic tool. Predictions are experimental and should not be used as a substitute for professional medical diagnosis or advice.

## Author

**Sirisha S**

GitHub: [sirii-18](https://github.com/sirii-18)

Project: [PARKIVOX](https://github.com/sirii-18/PARKIVOX)

---

⭐ If you find this project interesting, consider giving it a star!
