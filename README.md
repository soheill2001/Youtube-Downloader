# Django YouTube Downloader

This Django web application allows users to download videos from YouTube by entering the video's URL. It utilizes the `pytube` library to fetch video details and download the video in various resolutions.

## Features

- Simple and modern UI
- Fetch video details using YouTube URL
- Download videos in different resolutions

## Prerequisites

Before you begin, ensure you have met the following requirements:

- You have a `Windows/Linux/Mac` machine.
- You have installed `Python 3.x` and `pip`.
- You have a basic understanding of Python and Django.

## Installation

To install Django YouTube Downloader, follow these steps:

1. Clone the repository:
```bash
git clone https://github.com/soheill2001/Youtube-Downloader.git
```

2. Navigate to the project directory:
```bash
cd Youtube-Downloader
```

3. Install the required dependencies:
```bash
pip install -r requirements.txt
```
Make sure you have pytube installed, which is used for fetching YouTube video details and downloading them.

4. Run the development server:
```bash
python manage.py runserver
```

5. Visit http://127.0.0.1:8000/ in your web browser to use the application.

## Usage
Enter a valid YouTube URL into the input field and click on "Fetch Video". The video details will appear along with the download options for various resolutions.

