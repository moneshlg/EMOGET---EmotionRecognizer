# Project Name : Emotion-recognition
# Table of Content :
1.[Description](#p1)

2.[Installations](#p2)

3.[Usage](#p3)

4.[Dataset](#p4)


<a id="p1"></a>
# Description:

Emotion Recognition is the process of using machine learning to "scan" your face or multiple faces to find out their emotions.


<a id="p2"></a>
# Installations:

You will need multiple packages (tensorflow, numpy, keras, imutils). Use anaconda for easier usage.

<a id="p3"></a>
# Usage:

When real_time_video is run, a window will display your webcamera screen. Then, faces on the screen will be recognised and their associated emotions will be ontop of their head.
There will be a chart on the top right of the screen showing the overall emotion captured and the percentage of the feeling changes over time.

> Demo

python real_time_video.py

## If you just want to run this demo instead of training the model from scratch, the following content can be skipped
> Train

python train_emotion_classifier.py


<a id="p4"></a>
# Dataset:

I have used [this](https://www.kaggle.com/c/3364/download-all) dataset

Download it and put the csv in fer2013/fer2013/

-fer2013 emotion classification test accuracy: 66%
