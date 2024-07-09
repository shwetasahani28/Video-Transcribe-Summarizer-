# Video-Transcribe-Summarizer-
Build a video transcript summarizer using Google Generative AI (GAA). 
In this project I have use my Google generative API and YouTube Transcript API to automate the extraction and summarization of video transcripts.

The project involves two main functions:

Extracting the transcript: Using the YouTube Transcript API, the script extracts the full transcript from a provided YouTube video URL.
Generating the summary: The GAA model takes the extracted transcript and a custom prompt as input. It then generates a concise summary based on the prompt's instructions.

## key points
The summary is generated within 250 words.
The prompt can be customized to tailor the summary to specific requirements.
Streamlit is used to create the web app interface.
The app takes a YouTube video URL as input and displays the video thumbnail and transcript.
The user can click a button to trigger the summary generation process.
The summary can be modified by altering the prompt to adjust the length, style, and content focus.
