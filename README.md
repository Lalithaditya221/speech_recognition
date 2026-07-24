# 🎙️ Real-Time Speech-to-Text & Voice Echo Application

A Python application that captures real-time speech from your microphone using Google's Speech Recognition API, prints the transcribed text to the console, and speaks it back using offline Text-to-Speech (`pyttsx3`).

---

## ✨ Features

- 🎧 **Ambient Noise Adjustment**: Automatically adjusts for background noise before listening.
- 🗣️ **Google Speech Recognition**: Converts live audio input into accurate text.
- 🔊 **Text-to-Speech (TTS) Response**: Echoes the recognized text using `pyttsx3`.
- 🔄 **Continuous Listening Loop**: Runs indefinitely in real-time until terminated.
- 🛡️ **Exception Handling**: Handles unknown audio errors and network request issues gracefully.

---

## 🛠️ Prerequisites & Requirements

- **Python**: Python 3.8 to 3.12 (Recommended for PyAudio compatibility)
- **Microphone**: Working audio input device

### Dependencies

- `SpeechRecognition`
- `pyttsx3`
- `PyAudio`

---

## 🚀 Installation & Setup

1. **Clone the repository:**
   ```bash
   git clone https://github.com/Lalithaditya221/speech_recognition.git
   cd speech_recognition
   ```

2. **Create and activate a virtual environment (optional but recommended):**
   ```bash
   python -m venv venv
   # On Windows:
   venv\Scripts\activate
   # On macOS/Linux:
   source venv/bin/activate
   ```

3. **Install required dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

   > 💡 **Note on PyAudio on Windows**:
   > If installing `PyAudio` via pip fails on Windows, install `pipwin` or download a pre-built `.whl` file:
   > ```bash
   > pip install pipwin
   > pipwin install pyaudio
   > ```

---

## 💻 Usage

Run the script using Python:

```bash
python Speech_To_Text.py
```

1. Speak into your microphone after launching.
2. The recognized text will be printed in the terminal.
3. The computer will read the text back to you using TTS.
4. Press `Ctrl + C` in your terminal to stop execution.

---

## 📁 Repository Structure

```
Speech_To_Text/
├── Speech_To_Text.py   # Main Python application
├── requirements.txt    # Required Python packages
├── .gitignore          # Git ignore rules
└── README.md           # Project documentation
```

---

## 📄 License

This project is open-source and available under the [MIT License](LICENSE).
