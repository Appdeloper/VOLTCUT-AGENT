Project: KILLFRAME-AGENT

Track: Creative Apps

Tool used: GitHub Copilot

Problem statement:
Free Fire creators spend hours manually editing montage videos and syncing cuts to music, which is time-consuming and inaccessible to beginners.

Solution:
An autonomous AI agent that analyzes a creator's style and automatically produces beat-synced montages from raw gameplay footage.

Agentic workflow:
1. Analyze — `style_analyzer` inspects YouTube metadata and builds a style profile.
2. Detect — `beat_detector` finds beat timestamps in the music.
3. Select — `clip_selector` ranks and chooses highlight clips based on motion.
4. Edit — `video_editor` trims and concatenates clips into the final montage.

Tech stack:
Python, yt-dlp, librosa, moviepy, ffmpeg, Groq API, GitHub Copilot

Market size:
Free Fire has 500 million downloads and thousands of active creators who would benefit from automated editing tools.

Future vision:
- Support multiple games (Valorant, COD Mobile, BGMI)
- Web UI for non-technical creators
- Direct upload to YouTube and social platforms

