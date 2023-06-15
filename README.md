# Notes
First off, I am new to borrowing code. The Apache License is from the VOSK speech recognition code.

This uses VOSK to handle the speech recognition, then Google translate to ... translate to English. Currently I use this in tandem with an audio program like Voice Meeter to loop the output audio back into input audio to then be translated. So I can live translate something like a video, or movie, or live stream.

# Instructions
Alright, just learned that there is a file size limit to Github so I can't add the VOSK model here.

## Step 1
Download a VOSK model of your choice right over here -> https://alphacephei.com/vosk/models (This should be the language you want to be translated) <br>
And put the model inside the Speech folder. Unzip it if you need to.
## Step 2
Look inside ***test_microphone.py*** and set the path of the model to be the one you downloaded. Should be below the imports. Then configure the languages you want to translate from and to (source=' ' and target=' ' respectfully). Where source is the language of the VOSK model.
![image](https://github.com/TheBurntFish/Microphone-Translator/assets/44887704/43c14b76-efbe-4561-8b3f-e23b0ffb39c1)

## Step 3
Run ***test_microphone.py*** and the command prompt should open with "Press Ctrl+C to stop the recording"

#
I most definitely missed something so also read the VOSK read me files. Probably need to do some pip installs that I forgot. <br>


