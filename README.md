# Multi Speaker classification

In this project I have used supervised learning to classify multi speaker and single speaker segments from a audio file.
The audio file chosen is a Republic TV debate available on YouTube.

The attributes taken for buidling the supervised learning models are : <br>
👉 Mean and Standard deviation of audio signal over 2 sec intervals.<br>
👉 Number and density of peaks<br>
👉 Sub-band energy ratio<br>

The following algorithms are used for classification:<br>
▶️ SGDClassifier<br>
▶️ KNN<br>
▶️ XGBoost<br>
▶️ Neural Networks<br>

The best accuracy on unseen data come out to be 81% using Neaural Networks. The performance can be further imporved
by adding more features using PyAudio library (Mel spectrum and other audio features)

Where can such analysis be used :
⏳ If you have spend 1 HR watching news, how much of it was really informational?
