# YouTube Video to Text Converter 📺➡️📝

[![Language](https://img.shields.io/badge/Language-Python%20%7C%20Jupyter-blue)](https://github.com/aeleraqi/-Youtube-Video-to-Text-Converter)
[![Stars](https://img.shields.io/github/stars/aeleraqi/-Youtube-Video-to-Text-Converter?style=social)](https://github.com/aeleraqi/-Youtube-Video-to-Text-Converter/stargazers)

Convert **YouTube videos** to text transcriptions automatically using Python.

## 📖 About

This notebook lets you extract a YouTube video's audio track and convert it to a text transcription — no manual downloading required. Ideal for researchers, journalists, students, and content creators.

## ✨ Features

- Download audio directly from any YouTube URL
- Automatic speech-to-text transcription
- Language auto-detection
- Export transcriptions to TXT or SRT format
- Works with long-form videos (lectures, interviews, podcasts)

## 🚀 Getting Started

```bash
pip install yt-dlp SpeechRecognition pydub
jupyter notebook
```

## 💡 Usage

```python
url = "https://www.youtube.com/watch?v=YOUR_VIDEO_ID"
transcript = youtube_to_text(url, language="en-US")
print(transcript)
```

---
**Author:** [Amr Eleraqi](https://github.com/aeleraqi) — Data Analyst | NLP Specialist | Machine Learning Expert | Educator  
**Affiliation:** Toronto Metropolitan University, Ontario, Canada  
[![ORCID](https://img.shields.io/badge/ORCID-0000--0003--0935--0026-brightgreen)](https://orcid.org/0000-0003-0935-0026) [![GitHub](https://img.shields.io/github/followers/aeleraqi?label=Follow&style=social)](https://github.com/aeleraqi)
