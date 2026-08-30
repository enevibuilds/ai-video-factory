AI Video Factory MVP

AI Video Factory is an automated video-generation pipeline designed to turn a topic or idea into a finished video using AI-generated scripts, narration, visual assets, and video composition.

🚀 What It Does

The MVP is designed around this pipeline:

Topic → AI Brain → Script → Voice → Visual Assets → Video Composition → Final Video

Core Components

- brain.py — Generates and structures the video content.
- audio.py — Creates narration/audio.
- assets.py — Handles visual assets used by the video.
- composer.py — Combines the narration and visual assets into the final video.

🛠️ Requirements

You will need:

- Python 3.10+
- Gemini API
- Pexels API
- Edge TTS
- FFmpeg

Python dependencies will be listed in "requirements.txt".

🔑 API Keys

API keys should be stored as environment variables.

Never commit API keys, passwords, or ".env" files to GitHub.

Example:

GEMINI_API_KEY=your_gemini_key
PEXELS_API_KEY=your_pexels_key

▶️ Running the Project

Clone the repository:

git clone https://github.com/enevibuilds/ai-video-factory.git
cd ai-video-factory

Install dependencies:

pip install -r requirements.txt

Configure your API keys as environment variables, then run the main pipeline according to the project entry point.

📁 Project Structure

ai-video-factory/
│
├── brain.py
├── audio.py
├── assets.py
├── composer.py
├── AI Video Factory MVP.zip
├── requirements.txt
├── .gitignore
└── README.md

🎯 MVP Goal

The goal of AI Video Factory is to make video production faster and more automated by connecting AI script generation, narration, visual assets, and video composition into one workflow.

🔒 Security

Do not upload:

- API keys
- ".env" files
- Passwords
- Authentication tokens
- Private credentials
- Generated media that does not belong in the repository

📌 Project Status

MVP — Active Development

The pipeline is currently being tested and improved for reliable end-to-end automated video generation.

🔮 Future Improvements

- Automated scene generation
- AI image generation
- Automatic captions
- Background music
- Multiple voice options
- Automatic YouTube formatting
- 9:16 Shorts generation
- 16:9 YouTube video generation
- One-click video production
- Web interface
- Automated publishing
