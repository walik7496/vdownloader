# YouTube Video Downloader using Python

This is a simple graphical user interface (GUI) application built with `Tkinter` and `pytube` libraries to download YouTube videos directly to your computer.

## Features
- Enter a YouTube video URL to download the video.
- Choose the destination folder for saving the video.
- Download the video with a single click.

## Requirements
To run this application, you'll need to install the following libraries:

- `Tkinter`: A Python library for creating GUI applications.
- `pytube`: A lightweight Python library for downloading YouTube videos.

You can install them using pip:

```bash
pip install pytube
```

Note: Tkinter is included with most Python installations by default, but if it is not available, you can install it depending on your operating system.

## How to Use

1. Enter YouTube URL:
   - In the "YouTube link" field, paste the link of the YouTube video you want to download.
2. Choose Destination Folder:
   - Click on the "Browse" button to choose a destination folder where the video will be saved.
3. Download Video:
   - After entering the link and choosing the folder, click the "Download Video" button to start the download. A success message will appear once the video is downloaded.

## Code Explanation
- Widgets Function: This function sets up the GUI elements, including labels, text entry fields, and buttons.
- Browse Function: Allows you to choose the folder where you want the video to be saved.
- Download Function: Downloads the video from the provided YouTube URL using pytube.

## Screenshots

You can imagine a simple window with:
- A text box for entering the YouTube link.
- A browse button for choosing the destination folder.
- A download button for starting the video download.

## License

This project is open source and free to use.
