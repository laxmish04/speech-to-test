# 🎙️ Speech to Text Converter

A simple and interactive Speech to Text web application built using **Python, Streamlit, and SpeechRecognition**.

Convert your speech into written text in multiple Indian languages, including English, Hindi, Kannada, and Malayalam.

## ✨ Features
- 🎤 Record audio directly through your microphone.
- 🌐 Supports four languages: English, Hindi, Kannada, and Malayalam.
- ⚡ Converts speech into text using Google Speech Recognition.
- 📄 Displays the transcribed text in an editable text area.
- 📥 Download the transcription as a `.txt` file.
- 🖥️ Simple and user-friendly interface.

## 🛠️ Technologies Used
- Python
- Streamlit
- SpeechRecognition
- Google Speech Recognition API

## 📦 Installation
 Install the required libraries:
   ```bash
   pip install streamlit SpeechRecognition
   ```

## 🚀 How to Run

Run the following command in your terminal:

```bash
streamlit run app.py
```

Replace `app.py` with your Python filename if it is different.

## 📖 How to Use
1. Launch the application.
2. Select your preferred language.
3. Click the microphone button and record your speech.
4. Click **Convert to Text**.
5. View the transcription and download it as a text file.

## ⚠️ Requirements
- Python installed on your system.
- A working microphone and browser microphone permission.
- Internet connection for Google Speech Recognition.
- Streamlit version 1.39 or later for `st.audio_input`.

## 🔮 Future Improvements
- Add more language options.
- Support uploading pre-recorded audio files.
- Add punctuation and improved transcription formatting.
- Integrate offline speech recognition.

## 👨‍💻 Author
Developed as a Python project to explore speech recognition and web application development.

## 📜 License
This project is available for educational and learning purposes.
