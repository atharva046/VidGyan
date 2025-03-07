# 📽️ VidGyan - Educational Video Generation App

## 📌 Overview
VidGyan is a Flask-based web application that generates educational videos based on text prompts. It fetches relevant images, creates a slideshow, generates audio narration, and synchronizes everything into a video. 🎥✨

## 🚀 Features
- 🔍 Fetches topic-related images using Google Custom Search API
- 📝 Generates an educational script with Gemini AI
- 🎤 Converts text to speech using gTTS
- 🖼️ Creates a slideshow video with synchronized audio
- 🎬 Outputs a final educational video

## 🛠️ Technologies Used
- 🐍 **Flask** - Web framework
- 🎨 **HTML, CSS, JavaScript** - Frontend
- 🖼️ **PIL (Pillow)** - Image processing
- 🔊 **gTTS** - Text-to-speech conversion
- 🎥 **MoviePy** - Video generation
- 🤖 **Google Gemini AI** - Script generation
- 🔍 **Google Custom Search API** - Image fetching

## 📂 Folder Structure
```
VidGyan/
│-- static/              # Static files (CSS, JS, images, generated videos)
│-- templates/           # HTML templates
│-- app.py               # Main Flask application
│-- requirements.txt     # Python dependencies
│-- README.md            # Project documentation
```

## 🚀 Setup & Installation
1. 📥 Clone the repository:
   ```bash
   git clone https://github.com/atharva046/VidGyan.git
   cd VidGyan
   ```
2. 🐍 Create a virtual environment and activate it:
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows use: venv\Scripts\activate
   ```
3. 📦 Install dependencies:
   ```bash
   pip install flask pillow gtts moviepy requests google-generativeai
   ```
4. 🔑 Set up API keys:
   - Replace placeholders in `app.py` with your API keys for:
     - Google Custom Search API
     - Google Gemini AI API
5. ▶️ Run the application:
   ```bash
   python app.py
   ```
6. 🌐 Open in your browser: `http://127.0.0.1:5000`

## 🎯 Usage
1. 🔎 Enter a topic and select difficulty.
2. 📝 The app generates an educational script.
3. 🎬 Video is created with images & narration.
4. 📥 Download the final video.

## 🤝 Contributing
We welcome contributions! Fork the repo, create a new branch, and submit a PR. 🚀

## 📄 License
MIT License. Feel free to use and modify! 🔥

