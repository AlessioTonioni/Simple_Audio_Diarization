# Simple_Diarization

This is a very simple colab putting together a few models from Hugging Face to implement a simple audio to text + diarization script. The audio to text is implemented using different versions of Whisper including a small one fine tuned for Swiss German. 

I was looking for this functionality online and only found very confusing blog posts explaining very unnecessary features and sorta obscure pipelines, hence why I decided to re-implement it in what I believe being a very simple way. 

The colab does 4 things:
* Let you upload an audio file
* Run Whisper over the file to get a transcription
* Run an additional model to classify speakers and map them to intervals of time
* Map whisper transcriptions to the speakers to print a diarization. 

