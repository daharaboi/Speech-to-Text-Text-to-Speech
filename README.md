# Speech-to-Text-Text-to-Speech
Welcome to the Speech-Text-Module-Python repository! This repository contains a Python module that offers both Speech to Text (STT) and Text to Speech (TTS) functionalities. You can choose whether to transcribe spoken language into text or convert written text into synthesized speech.
Module: speech_text_module.py

Features:

Speech to Text (STT):

Utilizes the SpeechRecognition library to capture audio input from a microphone and transcribe it into textual format.
Demonstrates error handling for scenarios where the speech cannot be recognized or there's an API request error.
Implements Google Web Speech API for accurate speech recognition.
Text to Speech (TTS):

Utilizes the pyaudio library for capturing and playing audio.
Utilizes the googletrans library for language translation, enhancing the TTS functionality by generating speech in different languages.
Integrates the gTTS (Google Text-to-Speech) library to convert text into natural-sounding speech.
Provides functionality to save the synthesized speech as an audio file and play it back.
Usage:

Clone the repository to your local machine.
Navigate to the repository's directory.
Import the speech_text_module module into your Python script.
Choose the functionality you want to use:
For Speech to Text, call speech_text_module.stt() function.
For Text to Speech, call speech_text_module.tts() function.
Follow the on-screen prompts and instructions to interact with the chosen functionality.
