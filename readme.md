# 🎙️ Background Speech Recognition with Python

This Python script listens to the microphone in the background and transcribes spoken words into text using Google Speech Recognition.

---

## 📖 Overview

This project uses the `speech_recognition` library to:
- Continuously listen to audio from the microphone.
- Transcribe speech in real-time using Google's Web Speech API.
- Handle recognition asynchronously while other tasks run in the main thread.

---

## 🧰 Technologies Used

| Technology             | Purpose                                                        |
|------------------------|----------------------------------------------------------------|
| `speech_recognition`   | Interface to speech recognition engines (Google Web Speech)    |
| `pyaudio`              | Accesses microphone audio input                                |
| `time` (Python stdlib) | Used to simulate unrelated processing while audio is captured  |

---

## 🛠️ Usages

This script can be used for:
- Voice assistants
- Real-time transcription
- Hands-free command systems
- Voice-based logging or controls

---

## 📦 Install Dependencies

Install the required Python libraries using `pip`:

```bash
pip install SpeechRecognition pyaudio
