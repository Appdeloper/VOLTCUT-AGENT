
# 🎮 KILLFRAME-AGENT

> **KILLFRAME-AGENT is an autonomous AI agent built for the Microsoft Agents League Hackathon that watches, learns, and edits like a pro gaming content creator — automatically.**



![Python](https://img.shields.io/badge/Python-3.10+-blue?style=for-the-badge&logo=python)




![GitHub Copilot](https://img.shields.io/badge/Built%20With-GitHub%20Copilot-black?style=for-the-badge&logo=github)




![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)




![Hackathon](https://img.shields.io/badge/Microsoft-Agents%20League%202026-orange?style=for-the-badge&logo=microsoft)



---

## 🔥 What Is KILLFRAME-AGENT?

KILLFRAME-AGENT is an **autonomous AI agent** that studies a Free Fire gaming creator's YouTube channel, learns their unique editing style, and automatically produces a professional beat-synced montage from raw gameplay footage — with zero manual editing required.

Point it at a YouTube channel. Give it your gameplay clips and a track. It does the rest.

---

## 🤖 How The Agent Works

```

📺  INPUT: YouTube Channel URL + Raw Gameplay Footage + Music File
          │
          ▼
🔍  STEP 1 — STYLE ANALYZER
    # 🎮 KILLFRAME-AGENT

    ![Python](https://img.shields.io/badge/Python-3.10+-blue?style=for-the-badge&logo=python) ![FFmpeg](https://img.shields.io/badge/FFmpeg-required-red?style=for-the-badge) ![Groq](https://img.shields.io/badge/Groq-LLM-blue?style=for-the-badge)

    Built for Microsoft Agents League Hackathon 2026 — Creative Apps Track

    ---

    ## How it works (4 steps)

    1. Analyze: `style_analyzer` inspects a creator's YouTube metadata to infer editing style.
    2. Detect: `beat_detector` finds beat timestamps from the music track.
    3. Select: `clip_selector` ranks gameplay clips by motion intensity and selects highlights.
    4. Edit: `video_editor` trims and concatenates clips to produce a beat-synced montage.

    ---

    ## Tech stack

    | Tool | Purpose |
    |---|---|
    | Python | Core language |
    | yt-dlp | YouTube metadata/downloads |
    | librosa | Audio beat detection |
    | moviepy | Video editing |
    | ffmpeg | Encoding and processing |
    | Groq API | LLM style analysis |
    | GitHub Copilot | Development assistant |

    ---

    ## Quick run (3 commands)

    ```powershell
    pip install -r requirements.txt
    python demo.py --youtube "https://www.youtube.com/@RuokFF" --footage "./test_footage" --music "./test_music.mp3" --output "./demo_montage.mp4"
    ```

    Demo video link: Demo video link here

    ---

    For full development docs and API key setup, see `DEMO.md` and the repository files.

- [ ] Support for multiple games (Valorant, BGMI, COD Mobile)
- [ ] Style presets from top 100 gaming creators
- [ ] Real-time clip suggestion during live gameplay
- [ ] Direct upload to YouTube & Instagram Reels
- [ ] Web UI for non-technical creators

---

## 👤 Author

Built with 🔥 for the Microsoft Agents League Hackathon 2026.

---

## 📄 License

MIT License — free to use, modify, and distribute.
```