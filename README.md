# Speech-Emotion-Recognition
Speech Emotion Recognition(SER) is the act of attempting to recognize human emotion and affective states from speech. This is capitalizing on the fact that voice often reflects underlying emotion through tone and pitch. This is also the phenomenon that animals like dogs and horses employ to be able to understand human emotion.

*Librosa*

Librosa is a Python library for analyzing audio and music. It has a flatter package layout, standardizes interfaces and names, backwards compatibility, modular functions, and readable code. 

Installing librosa library: 
> pip install librosa soundfile

*Objective*

To build a model to recognize emotion from speech using the librosa, soundfile, and sklearn (among others) to build a model using an MLPClassifier. This will be able to recognize emotion from sound files. We will load the data, extract features from it, then split the dataset into training and testing sets. Then, we’ll initialize an MLPClassifier and train the model. Finally, we’ll calculate the accuracy of our model.

*Dataset*
For this Python mini project, we’ll use the RAVDESS dataset. Tthis is the Ryerson Audio-Visual Database of Emotional Speech and Song dataset, and is free to download. This dataset has 7356 files rated by 247 individuals 10 times on emotional validity, intensity, and genuineness. The entire dataset is 24.8GB from 24 actors, but we’ve lowered the sample rate on all the files, and you can download it here: *https://drive.google.com/file/d/1wWsrN2Ep7x6lWqOXfr4rpKGYrJhWc8z7/view*

*Prerequisites*

> librosa 
> soundfile 
> numpy 
> sklearn
> pyaudio







Reference: Zenodo(https://zenodo.org/record/1188976#.Xb3Zn-Yza92)
