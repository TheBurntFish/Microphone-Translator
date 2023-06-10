# Notes
First off, I am new to borrowing code. I think I credited the VOSK speech recognition code sufficiently with the Apache License. <br>
If not, I am sorry please don't sue me.

This uses VOSK to handle the speech recognition, then Google translate to ... translate to English. Currently I use this in tandem with an audio program like Voice Meeter to loop the output audio back into input audio to then be translated. So I can live translate something like a video, or movie, or live stream.

Anyways, just open this up and run the test_microphone.py. Not entirely sure if you need Visual Studio but that's what I use. This is currently setup to translate Japanese to English though I suppose you could download another language model for VOSK right here -> https://alphacephei.com/vosk/models and fiddle with the code to use the new model and/or change the resulting language.
