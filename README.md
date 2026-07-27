# 🚀 YouTube Advanced Downloader (Google Colab)

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/pixovia/yt-multi-quality-downloader/blob/main/Yt_multi_quality_downloader.ipynb)

A powerful, interactive, and user-friendly Google Colab notebook for downloading YouTube videos in various formats and qualities. Powered by `yt-dlp`.

## ✨ Features

This notebook provides a seamless UI right inside Google Colab (using form fields) so you don't have to edit any code. It includes the following versatile download modes:

- **🎬 Video + Audio**: Standard download of the video with its audio track muxed together.
- **🎵 Audio Only**: Extracts the audio track and converts it to MP3 format automatically.
- **🔕 Video Only**: Downloads only the video stream without any audio.
- **✂️ Separate Video and Audio**: Downloads both tracks as individual, separate files in one go.

### 📶 Quality Presets
- **Best Quality**: Fetches the highest resolution video and highest bitrate audio available.
- **Low (Data Saver)**: Specifically designed for users with low bandwidth or older devices, automatically picking the smallest available files.

## 🚀 How to Use

1. **Open the Notebook**: Upload `Yt_multi_quality_downloader.ipynb` to [Google Colab](https://colab.research.google.com/).
2. **Install Dependencies**: Run the first cell to install `yt-dlp`.
3. **Configure Settings**: In the second cell, paste your YouTube URL, select your desired **Download Type** and **Quality Preset** from the dropdown menus.
4. **Run the Cell**: Execute the cell to start the download directly to your Colab environment.
5. **Download to Local Device**: Run the final step in the notebook to bundle and download the generated media files directly to your computer.

## ⚙️ Advanced Options

For power users who need exact control over resolutions, frame rates, and codecs, the notebook includes an **Advanced Format Selection** section. You can list all available formats for a video and download a specific one using its unique `Format ID`.

## 📦 Requirements
- A Google Account (to use Google Colab)
- The notebook handles the installation of `yt-dlp` and depends on Colab's pre-installed `ffmpeg` for media merging and extraction.
