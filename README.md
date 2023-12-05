# YouTube Transcript Summarizer

This Python script uses the OpenAI API and the YouTube Transcript API to fetch a video transcript and generate a summary of it.

## Prerequisites

- Python 3.11 or higher
- An OpenAI API key

## Installation

Install the required Python packages using pip:

```bash
pip install -r requirements.txt
```

Set your OpenAI API key as an environment variable:
```bash
export OPENAI_API_KEY=your-api-key
```

## Usage
Run the script from the command line, passing the YouTube video ID as an argument:

```bash
python youtube.py --VideoId your-video-id
```