## yt-dlp-sh

Minimalist PowerShell script for batch downloading videos. Simple, fast and stable.

### Features
- **Hotkeys:** Instant resolution selection using `0-6`, `Enter` (1080p), or `Backspace` (720p).
- **Efficient Codecs:** Automatically prioritizes **AV1** and **VP9** for the smallest file sizes.
- **Audio Mode:** Dedicated "Audio Only" (M4A) mode via hotkey `0`.
- **Smart Playlists:** Auto-creates subfolders and maintains indexing for playlists.
- **Preview Support:** Uses MKV container to allow watching files during the download.
- **Resumable:** Handles HLS fragments and supports resuming interrupted tasks.

### Setup
1. Open `run.ps1`.
2. Set your paths for `yt-dlp`, `ffmpeg`, and `deno`.
3. Run the script.

### 📦 Requirements
- [yt-dlp](https://github.com/yt-dlp/yt-dlp)
- [FFmpeg](https://ffmpeg.org/)
- [Deno](https://deno.com/) (recommended)
