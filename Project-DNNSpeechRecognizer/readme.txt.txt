#Oushesh Haradhun

We will work with the LibriSpeech dataset. For more powerful datasets check: http://www.openslr.org/12/

Steps>Convert raw audio data to feature representations > Map Audio features to transcribed text

This project has 3 steps:

Step 1-Feature Extraction
Step 2- Accoustic Model
Step 3- Decoder 


For further reading on interesting Papers:
1.https://www.semanticscholar.org/paper/Learning-the-speech-front-end-with-raw-waveform-Sainath-Weiss/a566cd4a8623d661a4931814d9dffc72ecbf63c4

2. For feature Extraction we have 2 options:
	Option 1: Spectogram https://github.com/baidu-research/ba-dls-deepspeech
	Option 2: Mel-Frequency Cepstral Coefficients (MFCCs)� https://github.com/jameslyons/python_speech_features


To construct the pipeline you can choose either spectogram or MFCC features.

-> https://github.com/baidu-research/ba-dls-deepspeech -- Spectogram
-> 