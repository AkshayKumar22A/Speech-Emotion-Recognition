# Speech-Emotion-Recognition
The main goal and objective for the project undertaken are to created a working model of Emotion Recognition in speech Using Machine learning in Python and combine four different standard datasets. Participated and presented research paper on Exploring the Emotion Recognition in speech Using Machine Learning in the 2nd International Conference on Information Technology (InCITe) 2022
***

## About Authors & Paper
This repository contains the source code used in the following paper,
Exploring the Emotion Recognition in Speech Using Machine Learning [Paper Link](https://link.springer.com/chapter/10.1007/978-981-19-7346-8_64#citeas) <br>
#### [Akshay Kumar](https://github.com/AkshayKumar22A) <br>
Email: akshaykumar22a@gmail.com

## Databases Used for SER project
1. [Crowd-sourced Emotional Mutimodal Actors Dataset (Crema-D)](https://github.com/CheyneyComputerScience/CREMA-D), contain 7442 original audio clips from 91 actors in which 48 were male and 43 were female actors aged between 20 to 74 belonging to various culture, race, places, and ethnicities.
3. [Ryerson Audio-Visual Database of Emotional Speech and Song (Ravdess)](https://zenodo.org/records/1188976), with 24 professional actors ,12 male speakers and 12 Female speakers, the lexical features (vocabulary) of the utterances are kept constant by speaking only 2 statements of equal lengths in 8 different emotions by all speakers. We got 7356 audio samples ((Total size: 24.8 GB).
4. [Surrey Audio-Visual Expressed Emotion (Savee)](http://kahlan.eps.surrey.ac.uk/savee/Download.html), recording of four native English male speakers aged between 27 and 31 years. 
5. [Toronto emotional speech set (Tess)](https://tspace.library.utoronto.ca/handle/1807/24487) dataset contains 2800 files which are set of 200 targeted words spoken in the phrases of “Say the word ____” by two native speaking English actresses aged 26 and 64 years old.
***

## Environments
Python 3.8
Keras & TensorFlow 2
***

## Requirments
### Python
* [TensorFlow 2](https://github.com/tensorflow/tensorflow) & [Keras](https://github.com/keras-team/keras): CNN (tensorflow.keras)
* [Scikit-learn](https://github.com/scikit-learn/scikit-learn): SVM & MLP, split data into training set and testing set
* [Joblib](https://github.com/joblib/joblib)：save and load models trained by scikit-learn
* [librosa](https://github.com/librosa/librosa): extract features, waveform
* [SciPy](https://github.com/scipy/scipy): spectrogram
* [pandas](https://github.com/pandas-dev/pandas): load features
* [Matplotlib](https://github.com/matplotlib/matplotlib): plot graphs
* [NumPy](https://github.com/numpy/numpy)
* [Seaborn](https://github.com/mwaskom/seaborn)
***

## Emotions available
There are 7 emotions available for both Male and Femail: "neutral", "happy" "sad", "angry", "fear", "disgust" and "surprise".
***

## Feature Extraction
Feature extraction is the main part of the speech emotion recognition system. It is basically accomplished by changing the speech waveform to a form of parametric representation at a relatively lesser data rate.
In this repository, we have used the most used features that are available in librosa library including:
* MFCC
* Chromagram
* MEL Spectrogram Frequency (mel)
* Contrast
***

## License
Please read LICENSE file.
***

## References / Citation
* [Ayadi ME, Kamel MS, Karray F (2011) Survey on speech emotion recognition: features, classification schemes, and databases. Pattern Recogn](https://scholar.google.com/scholar?&q=Ayadi%20ME%2C%20Kamel%20MS%2C%20Karray%20F%20%282011%29%20Survey%20on%20speech%20emotion%20recognition%3A%20features%2C%20classification%20schemes%2C%20and%20databases.%20Pattern%20Recogn%0A)
* [Jackson P, Haq S (2011) Surrey audio-visual expressed emotion (SAVEE) database.](http://kahlan.eps.surrey.ac.uk/savee/Database.html)
* [Livingstone SR, Russo FA (2018) The Ryerson audio-visual database of emotional speech and song (RAVDESS): a dynamic, multimodal set of facial and vocal expressions in North American English. PLoS ONE 13(5), Article e0196391.](https://doi.org/10.1371/journal.pone.019639)
* [Cao H, Cooper DG, Keutmann MK, Gur RC, Nenkova A, Verma R (2014) CREMA-D: crowd-sourced emotional multimodal actors dataset. IEEE Trans AffectComput 5(4):377–390.](https://doi.org/10.1109/TAFFC.2014.2336244)
* [Dupuis K, Pichora-Fuller MK (2010) Toronto emotional speech set (TESS). Toronto, University of Toronto, Psychology Department](https://scholar.google.com/scholar?&q=Dupuis%20K%2C%20Pichora-Fuller%20MK%20%282010%29%20Toronto%20emotional%20speech%20set%20%28TESS%29.%20Toronto%2C%20University%20of%20Toronto%2C%20Psychology%20Department%0A)
* [Rong J, Li G, Chen YPP (2009) Acoustic feature selection for automatic emotion recognition from speech. Information Processing and Management 45 (Elsevier)](https://scholar.google.com/scholar?&q=Rong%20J%2C%20Li%20G%2C%20Chen%20YPP%20%282009%29%20Acoustic%20feature%20selection%20for%20automatic%20emotion%20recognition%20from%20speech.%20Information%20Processing%20and%20Management%2045%20%28Elsevier%29)
