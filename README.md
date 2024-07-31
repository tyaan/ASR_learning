# ASR_learning

Implementing the Automatic Speech Recognition parts of the book "Speech and Language Processing" V2 by Daniel Jurafsky and James H. Martin. \n
I'm doing this for learning purposes, following the old method of ASR using HMM's rather than new deep learning methods. \n
\n
I will use the "DARPA TIMIT Acoustic-Phonetic Continuous Speech" dataset to predict phones from speech audio.\n
\n
31/07/2024 \n
\n
Wrote functions to extract input features from audio. Total of 39 input features for each audio frame. \n
For each audio frame these are: \n
\n
12 MFCC \n
12 delta MFCC \n
12 double delta MFCC \n 
1 frame energy \n
1 frame delta energy \n
1 frame double delta energy \n
