# Youtube-transcript-summarizer # YouTube Transcript Summarizer

With the enormous number of video recordings being created and shared online, finding relevant information within longer videos has become a challenge. This project aims to automatically summarize video transcripts, allowing users to quickly identify important patterns and save time. The system will employ abstractive text summarization techniques from the field of Natural Language Processing (NLP) to generate concise summaries from video transcripts.

## Project Context

The project addresses the need for efficient information retrieval from video content. Users often lack the time to watch lengthy videos, and manual content scanning can be time-consuming. By generating text summaries from video transcripts, this project aims to streamline the process of obtaining crucial insights from video content.

## High-Level Approach

1. **Transcript Extraction**: Utilize a Python API to retrieve transcripts/subtitles for a given YouTube video ID.

2. **Text Summarization**: Apply text summarization using HuggingFace transformers, a leading NLP library that offers various models for abstractive summarization.

3. **Backend API**: Build a Flask backend REST API to expose the summarization service to clients. This API will take video IDs as input and return the summarized text.

4. **Chrome Extension**: Develop a Chrome extension that leverages the backend API to display the summarized text directly to users. This extension will enhance the user experience by providing easily accessible summarized content.

## Applications

- **Meetings and Video-Conferencing**: Transform voice to text and generate summaries from team meetings, aiding participants in quickly reviewing key discussion points.

- **Patent Research**: Extract the most salient claims across patents using the summarization tool, facilitating efficient patent analysis.

## How to Use

1. Clone this repository.
2. Open a terminal or command prompt.
3. Navigate to the repository's directory.
4. Set up the backend API by running the Flask app (see below).
5. Install the Chrome extension and configure it to use the backend API.

## Solution

The solution employs Python for scripting, HuggingFace transformers for text summarization, Flask for the backend API, and Chrome extension development tools for the user interface.

### Setting Up the Backend API

1. Install required dependencies using `pip install -r requirements.txt`.
2. Run the Flask app using `python app.py`.

### Chrome Extension

1. Load the Chrome extension files into the extension development environment.
2. Configure the extension to send requests to the backend API for summarization.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
