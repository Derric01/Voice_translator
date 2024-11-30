Voice Translator Overview
Objective
Build a real-time voice translator using Python, AssemblyAI (speech-to-text API), and Eleven Labs (text-to-speech API) that supports translations among at least 10 languages, including Tamil, Kannada, Hindi, Telugu, Marathi, French, English, German, Spanish, and Japanese.

Project Features
Speech Recognition:
Convert spoken input to text using AssemblyAI's API.

Translation:
Translate the recognized text into a target language using a translation API (Google Translate API or any other suitable library).

Text-to-Speech (TTS):
Convert the translated text back into speech using Eleven Labs TTS API.

Multilingual Support:
Support multiple source and target languages, allowing users to select the desired languages dynamically.

User Interface (Optional):
Build a simple command-line interface or GUI to make the translator more user-friendly.

System Architecture
Input:

The system captures audio from the microphone (using pyaudio or speech_recognition library).
Audio data is sent to AssemblyAI for transcription.
Processing:

The transcribed text is sent to a translation API.
The translated text is sent to Eleven Labs TTS for audio output.
Output:

The generated speech is played back using a speaker or saved as an audio file.
Technologies & APIs
Python Libraries:

speech_recognition: Captures and processes audio input.
requests: Sends API requests to AssemblyAI, translation API, and Eleven Labs.
playsound or pydub: Plays the translated audio output.
APIs:

AssemblyAI: Converts speech input to text (speech-to-text).
Google Translate API: Translates the text into the target language.
Eleven Labs: Converts translated text to speech (text-to-speech).
