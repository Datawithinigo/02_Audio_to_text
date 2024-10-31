# 02_Audio_to_tex:  Conversion using Whisper and Python

This project leverages OpenAI's Whisper model to transcribe audio files to text. Whisper is a powerful tool that uses deep learning to understand and convert audio inputs into text, supporting multiple languages with high accuracy.

## Features

- **Multilingual support**: Transcribe audio in various languages.
- **High accuracy**: Provides reliable transcription for clear and noisy audio.
- **Customizable output**: Save transcriptions in multiple formats (e.g., `.txt`, `.json`).

## Prerequisites

- Python 3.8+
- [OpenAI Whisper](https://github.com/openai/whisper)
- FFmpeg (for audio processing)

To install FFmpeg:

```bash
# Ubuntu
sudo apt update && sudo apt install ffmpeg

# MacOS (using Homebrew)
brew install ffmpeg
