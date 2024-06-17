# Voice-to-Text Project

This project focuses on converting spoken audio input into text using Python. It utilizes the PyAudio library for audio input handling and implements a graphical interface with IPython widgets in Jupyter notebooks.

## Features

- **Real-time Speech Recognition:** Converts spoken words into text in near real-time.
- **Interactive GUI:** Uses IPython widgets for a user-friendly interface with buttons for recording and stopping audio.
- **Customizable Settings:** Adjustable parameters such as sample rate and recording duration.
- **Modular Design:** Implements multithreading for simultaneous audio recording and transcription.

## Usage

1. **Recording:** Click the "Record" button to start capturing audio from the microphone.
2. **Transcription:** Simultaneously transcribe the recorded audio into text using a speech recognition engine.
3. **Display:** View transcription results in real-time within the GUI.

## Requirements

- Python 3.x
- PyAudio (`pip install pyaudio`)
- IPython widgets (`pip install ipywidgets`)

## Implementation Details

- **`record_microphone(chunk=1024)` Function:** Records audio input using PyAudio, storing captured audio frames.
- **Speech Recognition:** Processes recorded audio frames to extract spoken words, displaying text results.
- **Threading:** Utilizes threads for concurrent recording and transcription tasks, ensuring efficient operation.

## Next Steps

- Customize speech recognition settings or integrate with additional processing for enhanced functionality.
- Expand GUI capabilities or integrate with other applications for broader use cases.

