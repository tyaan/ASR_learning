# ASR_learning

Implementing the Automatic Speech Recognition parts of the book "Speech and Language Processing" V2 by Daniel Jurafsky and James H. Martin. 
I'm doing this for learning purposes, following the old method of ASR using HMM's rather than new deep learning methods. 

I will use the "DARPA TIMIT Acoustic-Phonetic Continuous Speech" dataset to predict phones from speech audio.

31/07/2024

Wrote functions to extract input features from audio. Total of 39 input features for each audio frame. 
For each audio frame these are:

12 MFCC
12 delta MFCC
12 double delta MFCC
1 frame energy
1 frame delta energy
1 frame double delta energy
