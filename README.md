# ASR_learning

Implementing the Automatic Speech Recognition parts of the book "Speech and Language Processing" V2 by Daniel Jurafsky and James H. Martin. 
I'm doing this for learning purposes, following the old method of ASR using HMM's rather than new deep learning methods. I will mostly avoid using libraries for things like MFCC computation and do everything from scratch to help me understand the concepts. 

I will start by predicting phones from speech audio. I will use the DARPA TIMIT dataset containing speech audio and transcribed phones - https://www.kaggle.com/datasets/mfekadu/darpa-timit-acousticphonetic-continuous-speech

31/07/2024 

Wrote functions to extract input features from audio. Total of 39 input features for each audio frame. 
For each audio frame these are: 

12 MFCC 
12 delta MFCC 
12 double delta MFCC 
1 frame energy 
1 frame delta energy 
1 frame double delta energy 
