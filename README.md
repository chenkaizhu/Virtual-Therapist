# Virtual Therapist

The [**result.ipynb**](https://github.com/chenkaizhu/Virtual-Therapist/blob/master/result.ipynb) is part of an accessible mental health counseling platform that detects speech emotion and responds to verbal distress signals.

<!-- ![](voice_diagram.png?raw=true)
<br>
## CNN Model
![](cnn.png?raw=true)
<br> -->

## Emotion Recognition
This step involves extracting the features, such as its pitch and loudness from the audio files which will help our model learn between these audio files leveraging [**LibROSA**](https://librosa.github.io/librosa/) library in python.
<br>
![](feature.png?raw=true)
<br>

<br>

**The extracted features looks as follows**

<br>

![](feature2.png?raw=true)

<br>



## Predictions

Here are a sample of the actual vs predicted values after fine tuning the model.
<br>
<br>
![](predict.png?raw=true)
<br>



## Testing out with live voices.
The user is able to import his/her own .wav file to test against the model.
![](livevoice.PNG?raw=true)
<br>
<br>
![](livevoice2.PNG?raw=true)
<br>

0 - female_angry <br>
1 - female_calm <br>
2 - female_fearful <br>
3 - female_happy <br>
4 - female_sad <br>
5 - male_angry <br>
6 - male_calm <br>
7 - male_fearful <br>
8 - male_happy <br>
9 - male_sad <br>

### Datasets:
1. [RAVDESS](https://zenodo.org/record/1188976)
2. [SAVEE](http://kahlan.eps.surrey.ac.uk/savee/Download.html)

## Conclusion
The model was tuned to detect emotions with more than 70% accuracy to distinguish between male and female voices and their respective emotions. 
