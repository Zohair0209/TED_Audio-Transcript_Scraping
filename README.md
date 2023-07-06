# TED_Audio-Transcript_Scraping

### This project has been implemented on the URL: https://www.ted.com/talks

<hr>

This repository contains the Python codes for the following tasks:
1. Scraping video files and extracting audio from them.
2. Scraping English and Hindi transcript files for the respective videos.
3. Parsing through the transcript file, matching the sentences and their timestamps from the transcript to their respective audio file, and thereby splitting the audio file into corresponding segments.

<hr>

### List of Files:
1. Video_URL_List.txt : contains the list of URLs from the parent URL, linking to the respective webpages containing the TED videos.
2. videoScraping_convertToaudio.ipynb : contains the code for scraping video from the URL, extracting audio, and eventually deleting the video files to save on disk space.
3. transcript.ipynb : contains the code for scraping transcript files from the URL
4. speechTotext.ipynb : contains the code for parsing through the transcript file, matching the sentences and their timestamps from the transcript to their respective audio file, and thereby splitting the audio file into corresponding segments.

### List of Folders:
1. Videos: contains folder-wise extracted audio files along with their split segments corresponding to the timestamps in the transcript files.
2. VTT_Scripts: contains the folder-wise English and Hindi transcripts corresponding to the respective audio files.

<hr>

Note: Do change the paths to your local directories as mentioned through the passage of the Python codes.
