<h1> YouTube Video Summerizer </h1> <br>
 
<h2> Why YouTube Summerizer </h2>
For many videos, the main content of the videos is only 50-60% of the total length.Youtube summarizer will summarize the content of the video by keeping all the important points and making it short and easily understandable. Summarizing transcripts of such videos automatically allows us to quickly look out for the important patterns in the video and helps us to save time and efforts to go through the whole content of the video.

<h2> Project Features </h2>
1. Video Transcript Extraction : Automatically extracts transcripts from YouTube videos using the video URL.<br>
2. Transcription : Accessing the textual content of YouTube videos using YouTube Transcript API <br>
3. Summerization : We are using extractive summarization using SpaCy. Other techniques like TextRank, which is also available in SpaCy, or neural network-based models like BERT, GPT or summarization algorithms including Gensim, NLTK and TF-IDF can be used for more advanced summarization task. <br>

<h2> Installations </h2>
!pip install -q transformers </br> 
!pip install -q youtube_transcript_api </br>
pip install youtube-transcript-api </br>
pip install -U spacy </br>
 

<h2> Examples </h2>
 youtube_video = "https://www.youtube.com/watch?v=0p0o5cmgLdE </br>
 youtube_video ="https://www.youtube.com/watch?v=lrEkYscgbqE&t=1s </br>
