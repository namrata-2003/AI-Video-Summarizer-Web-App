# 🎥 AI Video Summarizer Web App

This AI-powered web application extracts audio from uploaded videos, converts it to text using speech recognition, summarizes it using a BERT-based NLP model, and provides both a **textual** and **audio** summary.  
Built with Django, Hugging Face Transformers, MoviePy, and gTTS.

---

## 📌 Features

- Upload video files (MP4, AVI, etc.)
- Extract and transcribe speech from videos using SpeechRecognition
- Summarize transcriptions using `facebook/bart-large-cnn`
- Get concise textual summaries
- Convert summaries to audio using `gTTS`
- Django-powered web interface

---

## 🧰 Tech Stack


Backend Framework: Django                               
Video Processing: MoviePy                              
Speech-to-Text: SpeechRecognition (Google API)       
Text Summarization: Transformers (BART model)          
Text Chunking: NLTK                                 
Text-to-Speech: gTTS (Google Text-to-Speech)         



