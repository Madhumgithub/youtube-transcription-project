# YouTube Video Transcription Project

## Overview
This project converts audio from YouTube videos into text. It utilizes `yt-dlp` for downloading videos and the Wav2Vec2 model for transcription. The project includes features like audio preprocessing and accurate speech-to-text conversion.

## Features
- Download YouTube videos and extract audio
- Preprocess audio for better transcription accuracy
- Generate transcripts with timestamps

## Requirements
- Python 3.x
- Required libraries specified in `requirements.txt`

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/YourUsername/youtube-transcription-project.git
   ```
2. Navigate to the project directory:
   ```bash
   cd youtube-transcription-project
   ```
3. Set up a virtual environment and install dependencies:
   ```bash
   python -m venv env
   source env/bin/activate  # On Windows use `env\Scripts\activate`
   pip install -r requirements.txt
   ```

## Usage
1. Place your YouTube video file in the `data` folder.
2. Run the transcription script:
   ```bash
   python src/YouTubeTranscriber.py
   ```
3. The transcription will be saved as `Transcripted_Text.txt`.

## Contributions
Feel free to fork the repository and submit pull requests.

