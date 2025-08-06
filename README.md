# Tonalure

## Purpose
This application allows users to upload a song, mark their favorite sections, and recieve insights about what makes those part appealing or "alluring" (tempo, frequency, energy). Based on these insights the system will recommend similar songs.

## Core Features
- Upload songs (Mp3, WAV)
- Generate Visualize spectrograms
- Let users highlight favorite time ranges
- Extract Features from those ranges
- Recommend Similar songs based on those patterns

## Dependencies
- Python 3.11+
- [FFmpeg](https://ffmpeg.org/) – required for audio decoding (used by librosa)
    - Ensure `ffmpeg` is installed and added to your system PATH
- See `requirements.txt` for Python package dependencies (use venv for installation)

## Running Environment
- Create venv: python -m venv venv
    - Run venv: venv\Scripts\activate
- Run jupiter: Project Root > [jupyter notebook]