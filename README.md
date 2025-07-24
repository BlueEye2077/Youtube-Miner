# YT Miner 🎬

A powerful and user-friendly YouTube video and audio downloader built with Python. YT Miner offers both simple and advanced modes for downloading content with customizable quality options and additional features.

[![YT Miner Banner](https://i.postimg.cc/NFGySrK4/Screenshot-2025-07-24-195729.png)](https://postimg.cc/9RSFq0tR)

## ✨ Features

### 🎯 Core Features
- **Dual Mode Operation**: Simple mode for quick downloads, Advanced mode for power users
- **Video Downloads**: Download videos in various qualities (144p to 4K+)
- **Audio Extraction**: Extract audio in MP3, M4A, and other formats
- **Quality Selection**: Interactive quality picker with file size estimates
- **Progress Tracking**: Real-time download progress with elegant progress bars
- **Batch Processing**: Download multiple files in sequence

### 🛠️ Additional Features
- **Subtitle Support**: Download and embed subtitles (Arabic & English)
- **Thumbnail Embedding**: Automatically embed video thumbnails
- **Metadata Preservation**: Keep video information and metadata
- **Custom Output Paths**: Organized folder structure for downloads
- **Error Handling**: Robust error handling and retry mechanisms
- **Cookie Support**: Use cookies for enhanced compatibility

## 🚀 Installation

### Prerequisites
- Python 3.7 or higher
- FFmpeg (for video processing)

### Required Dependencies
```bash
pip install yt-dlp tqdm rich
```

### FFmpeg Installation
#### Windows
1. Download FFmpeg from [https://ffmpeg.org/download.html](https://ffmpeg.org/download.html)
2. Extract and add to system PATH

#### macOS
```bash
brew install ffmpeg
```

#### Linux (Ubuntu/Debian)
```bash
sudo apt update
sudo apt install ffmpeg
```

### Clone Repository
```bash
git clone https://github.com/yourusername/yt-miner.git
cd yt-miner
```

## 📋 Usage

### Basic Usage
```bash
python yt_miner.py
```

### Simple Mode (Recommended for beginners)
1. Select **Simple Mode** (option 1)
2. Enter the YouTube video URL
3. Choose your preferred quality from the displayed options
4. Select video format (MP4, MKV, etc.)
5. Optionally enable additional settings (subtitles, thumbnails, metadata)

[![Simple Mode Flow](https://i.postimg.cc/15jkghrR/image.png)](https://postimg.cc/2VncJttg)

---

### Advanced Mode (For power users)
1. Select **Advanced Mode** (option 2)
2. Enter the YouTube video URL
3. View detailed format information
4. Enter custom format combination codes
5. Download begins automatically

[![Screenshot-2025-07-24-201234.png](https://i.postimg.cc/zXyxLLf6/Screenshot-2025-07-24-201234.png)](https://postimg.cc/TpXVF3gJ)

---

## 🎛️ Features Breakdown

### Video Download Options
- **Quality Selection**: Choose from available resolutions (144p to 4K+)
- **Format Support**: MP4, MKV, WebM, and more
- **Size Estimation**: View approximate file sizes before download


### Audio Download Options
- **Format Support**: MP3, M4A, OGG, and more
- **Quality**: Best available audio quality
- **Metadata**: Preserve artist, title, and album information

[![image.png](https://i.postimg.cc/tg9SgpmM/image.png)](https://postimg.cc/cv5M9yWR)

---

### Additional Settings

#### Subtitle Options
- **Languages**: Arabic and English support
- **Embedding**: Automatically embed subtitles into video files
- **Separate Files**: Option to download subtitle files separately


#### Thumbnail Options
- **Auto-Embed**: Automatically embeding the thumbnail directly into video/audio files and an option to download the thumbnail separately
- **Separate Download**: Save thumbnail as separate image file
- **Format Conversion**: Automatic JPG conversion


#### Metadata Options
- **Video Information**: Preserve title, description, upload date
- **JSON Export**: Save detailed video information as JSON
- **Embedded Metadata**: Add metadata directly to downloaded files

[![Screenshot-2025-07-24-201807.png](https://i.postimg.cc/SNVmKvJD/Screenshot-2025-07-24-201807.png)](https://postimg.cc/xckwxgGz)

---

## 📁 File Organization

YT Miner automatically organizes downloads into structured folders:

```
Downloads/
├── Video/
│   ├── VideoTitle1.mp4
│   ├── VideoTitle2.mkv
│   └── ...
└── Audio/
    ├── AudioTitle1.mp3
    ├── AudioTitle2.m4a
    └── ...
```

## ⚙️ Configuration

### Cookie Support
Place your YouTube cookies in `www.youtube.com_cookies.txt` for enhanced compatibility with age-restricted or private content.

### Custom Settings
Modify the script parameters for:
- Default output formats
- Concurrent downloads
- User agent strings
- Retry attempts


---

## 🤝 Contributing

We welcome contributions! Please follow these steps:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request



---

**Made with ❤️ by BlueEye**
