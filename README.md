# Resolve Converter AAC to PCM

This script converts video files with unsupported audio codecs (e.g., AAC) to a format compatible with **DaVinci Resolve** on Linux. The resulting files are in `.mov` format with `pcm_s16le` audio.

## Features
- Converts unsupported audio codecs to PCM.
- Maintains original video quality.
- Processes multiple files in one command.

## Requirements
- [FFmpeg](https://ffmpeg.org/download.html) installed on your system.
  
- Debian/Ubuntu
    ```bash
  sudo apt install -y ffmpeg

- Arch Linux
  ```bash
  sudo pacman -S ffmpeg
  
- Fedora
  ```bash
  sudo dnf install -y ffmpeg ffmpeg-devel

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/aac-to-resolve.git
   cd aac-to-resolve
