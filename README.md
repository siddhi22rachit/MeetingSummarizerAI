# Meeting Summarizer
1.Project Description
The Meeting Summarizer addresses the problem of long meetings leading to missed information and reduced productivity by automatically converting meeting videos into concise summaries. It extracts audio from videos and transcribes spoken content, enabling users to quickly access essential points without watching the entire meeting.

2.Features
a.Extracts audio from video files.
b.Transcribes audio into text.
c.Provides a summarized output of meeting content.

3.Requirements
Python 3.x
Required libraries: moviepy, transformers, torch, pydub, numpy

4.Installation
Clone the repository:

bash

git clone https://github.com/yourusername/MeetingSummarizer.git
cd MeetingSummarizer
Create a virtual environment (optional but recommended):

bash

python -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`
Install the required packages:

bash

pip install -r requirements.txt
Usage
Place your meeting video file (e.g., video1.mp4) in the project directory.

Run the meeting.py script:

bash

python meeting.py

The script will:

Extract audio from the video file.
Transcribe the audio into text.
Display the summarized meeting content.
Output
The audio will be saved as audio.wav.
The summary will be printed in the console.
Notes
Ensure that the video file is in a supported format (e.g., MP4).
Depending on the length of the video, the processing time may vary.

