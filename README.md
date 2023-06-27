# YouTube Sentiment Analyzer

YouTube Sentiment Analyzer is a Python project that extracts audio from YouTube videos, performs sentiment analysis on the extracted audio using the AssemblyAI speech-to-text transcription service, and provides insights about the sentiments expressed in the video.

## Prerequisites

Before using this project, ensure that you have the following dependencies installed:

- Python 3
- youtube_dl
- requests

You can install the required dependencies by running the following command:

```shell
pip install youtube_dl requests
```

## Getting Started

Follow the steps below to get started with the YouTube Sentiment Analyzer:

1. Clone the repository to your local machine or download the project files.
2. Obtain an API key from AssemblyAI by signing up on their website.
3. Rename the `api_secrets.py.example` file to `api_secrets.py`.
4. Open the `api_secrets.py` file and replace the placeholder value for `API_KEY_ASSEMBLYAI` with your actual AssemblyAI API key.
5. Open the `main.py` file and modify it according to your requirements. You can uncomment the line `save_video_sentiments("https://youtu.be/e-kSGNzu0hM")` to analyze sentiments for a specific YouTube video.
6. Run the `main.py` script using the following command:

```shell
python main.py
```

The script will extract audio from the specified YouTube video, perform sentiment analysis using the AssemblyAI API, and display the sentiment analysis results.

## Customization

You can customize the project according to your needs:

- Modify the `main.py` file to analyze sentiments for different YouTube videos.
- Adjust the sentiment analysis threshold or add more sentiment categories in the `main.py` file to further analyze sentiments.
