# Real-time Audio Synthesis from Scrolling News Tickers in Live News Video Streams for Visually Impaired

## Description
This is a system to convert scrolling news ticker text in live video streams into clear, real-time audio. The goal is to provide an accessible information source for visually impaired individuals, promoting inclusivity and engagement.
The system uses motion-based text detection for specifically detecting ticker text in live videos, and subsequently extracting the ticker text using OCR. It also incorporates spell checkers and non-common string concatenation algorithms to
minimize textual errors and generate smooth text sentences. Finally, real-time text-to-speech technologies like PyTTS convert the text to audio. 
This system was developed as part of my college degree project, where I collaborated with [Indirakanth](https://github.com/indira1vik) in developing the implementation and documentation for our system.

## Dataset
All videos are live and extracted from online streaming services like YouTube, Twitch, etc., by filtering out videos containing scrolling ticker text regions. Some videos are downloaded from online sources like YouTube.

Example links:
1. [https://youtu.be/w9uJg68CV4g](https://youtu.be/w9uJg68CV4g)
2. [https://youtu.be/XWq5kBlakcQ](https://youtu.be/XWq5kBlakcQ)
3. [https://youtu.be/6HodCcEW_oQ](https://youtu.be/6HodCcEW_oQ)

## Software Requirements
1. Python 3
2. Python Library imports:
   - pyspellchecker - version 0.8.1 or above
   - pytesseract - version 0.3.10 or above
   - streamlink - version 6.5.1 or above
   - flask - version 3.0.2 or above
   - pyttsx3 - version 2.90 or above
   - opencv - version 4.9.0 or above

## Hardware Requirements
1. GPU (for speed)
2. A decent processor with 8GB RAM for running the video smoothly.

## Instructions
1. Get the source code.
2. Use the code in an IDE.
3. Give the command `python views.py`.
4. Click on the localhost link appearing on the command line prompt (Example: http://127.0.0.1:8087).
5. After it opens in the webpage, copy and paste any live video streaming link from the internet, or use any example links given on the webpage.
6. As the video plays, listen to the audio. Press 'q' to exit the window and view the intermediate results on the webpage.
