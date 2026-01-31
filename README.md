# 🚀🎬 PhiloShorts-AI
## AI Video Automation Framework for Philosophical Content

<p align="center">
  <a href="https://pypi.org/project/philoshorts-ai/">
    <img src="https://static.pepy.tech/personalized-badge/philoshorts-ai?period=month&units=international_system&left_color=blue&right_color=green&left_text=Downloads/month">
  </a>
</p>

<div align="center">
  ⚡ Automating short-form video creation about philosophy, wisdom, and existential topics ⚡
</div>
</br>

## 🎥 Showcase

PhilOShorts-AI generates engaging YouTube Shorts and TikTok videos about philosophical topics, wisdom, and meaningful content.

## 🌟 About This Project

PhilOShorts-AI is a powerful framework for automating philosophical content creation. It simplifies video creation, footage sourcing, voiceover synthesis, and editing tasks.

- 🎞️ **Automated editing framework**: Streamlines the video creation process with an LLM oriented video editing language.

- 📃 **Scripts and Prompts**: Provides ready-to-use scripts and prompts for various LLM automated editing processes.

- 🗣️ **Voiceover / Content Creation**: Supports multiple languages for voiceover creation.

- 🔗 **Caption Generation**: Automates the generation of video captions.

- 🌐🎥 **Asset Sourcing**: Sources images and video footage from the internet.

- 🧠 **Memory and persistence**: Ensures long-term persistence of automated editing variables.

## 🚀 Quick Start

### Prerequisites

- Python 3.8+
- API Keys for OpenAI and ElevenLabs
- FFmpeg installed

### Installation

```bash
pip install philosophs-ai
```

Or clone and install locally:

```bash
git clone https://github.com/xpe-hub/philoshorts-ai.git
cd philosophs-ai
pip install -r requirements.txt
```

### Configuration

Create a `.env` file with your API keys:

```
OPENAI_API_KEY=your_openai_api_key
ELEVENLABS_API_KEY=your_elevenlabs_api_key
PEXELS_API_KEY=your_pexels_api_key
```

### Usage

```bash
python run_philoshorts.py
```

This will launch a web interface where you can:
- Enter your topic (philosophy, wisdom, existential questions)
- Generate a script
- Create a video with AI voice and visuals
- Download the final video

## 📝 Content Ideas

PhilOShorts-AI excels at creating content about:

- Philosophical concepts and wisdom
- Existential questions and meaning of life
- Ancient philosophy (Stoicism, Epicureanism, etc.)
- Modern philosophy and critical thinking
- Quotes from famous philosophers
- Self-improvement and personal growth
- Mindful living and mental wellness

## 🛠️ How It Works

1. **Script Generation**: Uses GPT to generate engaging scripts about philosophical topics
2. **Voice Synthesis**: Converts text to natural-sounding audio using ElevenLabs
3. **Visual Sourcing**: Finds relevant imagery and video footage
4. **Video Assembly**: Combines all elements into a polished short video
5. **Auto-Publishing**: Ready for YouTube and TikTok upload

## Technologies Used

- **MoviePy**: Video editing and rendering
- **OpenAI**: Script generation and prompts
- **ElevenLabs**: Voice synthesis
- **EdgeTTS**: Free alternative voice synthesis
- **Pexels**: Stock footage and images
- **TinyDB**: Persistence for editing variables

## 📄 License

MIT License

## 🤝 Contributing

Contributions are welcome! Feel free to open issues or submit pull requests.
