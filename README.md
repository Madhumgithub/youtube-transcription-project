# YouTube Video Transcription Project

## Overview

This project provides a comprehensive solution for converting audio from YouTube videos into text. Leveraging powerful libraries such as **MoviePy**, **Pydub**, and **SpeechRecognition**, the script extracts audio, detects silence, and transcribes speech accurately. This tool is designed for users who want to easily generate text transcriptions of video content, facilitating accessibility and content creation.

## Features

- **Audio Extraction**: Extracts audio from YouTube video files using MoviePy.
- **Silence Detection**: Identifies silence segments to improve transcription accuracy using Pydub.
- **Speech-to-Text**: Transcribes audio into text using Google’s Speech Recognition API.
- **Timestamping**: Generates transcriptions with timestamps for each segment.
- **File Export**: Saves the transcription to a text file for easy reference.

## Requirements

To run this project, you'll need to have Python 3.x installed along with the following libraries:

- `moviepy`
- `pydub`
- `speech_recognition`

You can install the required libraries using pip:

```bash
pip install moviepy pydub SpeechRecognition

Installation

1.Clone the repository:

git clone https://github.com/Madhumgithub/youtube-transcription-project.git

2.Navigate to the project directory:

cd youtube-transcription-project

3.Install the required packages:

pip install -r requirements.txt

Usage

Place your YouTube video file (e.g., audio1.mp4) in the project directory.

Modify the video_path variable in the script to point to your video file:

python
Copy code
video_path = "C:\\path\\to\\your\\video\\audio1.mp4"
Run the script:

bash
Copy code
python src/YouTubeTranscriber.ipynb
After the transcription is complete, you will find the output saved in Transcripted_Text.txt.

Example Output
csharp
Copy code
[0.000] Speaker: Hello everyone in this English episode we will be focusing on English conversation.
[5.500] Speaker: Listening to English conversation is an essential part of improving your English language skills.
...
Error Handling
The script includes error handling for common issues, such as:

Audio extraction failures.
Inability to understand audio by Google Speech Recognition.
Network issues while requesting results from the Speech Recognition service.
