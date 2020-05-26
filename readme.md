# NLP involved in the Project IDA
Audio is sent to DEEP-LEARNING 7-LAYERED DNN Model , which considers spectrogram of the
audio and uses the Librosa library for classifying the particular emotions Angry, Sad, Disgust,
Surprised, and a testing accuracy of 75%.

The calls are classified based on following features in our DL Model:

# MelSpectrogram, MFCC, Spectral-Contrast, Chroma,Tonnetz

The text is prioritized using TF-IDF, Page Ranking, Cosine Similarity using steps:

## Pre-Processing-> TF-IDF Matrix -> Similarity Semantics -> Page ranking.

The tweets are prioritized using Integer Linear Programming methods like Primal and Dual, and using library such as 
# Textacy, Spacy, NLTK, PyMathProg. Achieved in 3 steps:

# 1.I want the total length of all the selected tweets to be less than some value L

# 2.If I pick some content word (out of my possible content words) , then I want to have at least
one tweet from the set of tweets which contain that content word, .

# 3.If I pick some tweet i (out of my possible tweets) , then all the content words in that tweet are
also selected.
