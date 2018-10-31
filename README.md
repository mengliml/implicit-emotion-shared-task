# LING530FA2-Implicit-Emotion-Shared-Task

LING530F: Deep Learning for NLP Assign. 2: (Text) Classification With RNNs/LSTMs Format

This task was part of an EMNLP workshop as described [here](http://implicitemotions.wassa2018.com/). The task aims at "developing models which can classify a text into one of the following emotions:
Anger, Fear, Sadness, Joy, Surprise, Disgust without having access to an explicit mention of an emotion word."

### Task Description 
Participants were given a tweet from which a certain emotion word is removed. That word is
one of the following: “sad”, “happy”, “disgusted”, “surprised”, “angry”, “afraid” or a synonym of one of them. The task was to predict the emotion the excluded word expresses: Sadness, Joy, Disgust, Surprise, Anger, or Fear.
With this formulation of the task, we provide data instances which are likely to express an emotion. However, the emotion needs to be inferred from the causal description, which is typically more implicit than an emotion word. We therefore presume that successful systems will take into account world knowledge in a structured or statistical manner. Examples are:
* “It’s [#TARGETWORD#] when you feel like you are invisible to others.”
* “My step mom got so [#TARGETWORD#] when she came home from work and saw
that the boys didn’t come to Austin with me.”
* “We are so [#TARGETWORD#] that people must think we are on good drugs or just really good actors.”
The shared task consisted of the challenge to build a model which recognizes that [#TAR- GETWORD#] corresponds to sadness (“sad”) in the first two examples and with joy (“happy”) in the third.

### Models 
We develop a neural language model (language decoder) using the Long short term memory (LSTM) networks. you can go to the jupyter notebook file [A2](https://github.com/Mengsuper/LING530FA2-Implicit-Emotion-Shared-Task/blob/master/a2_final.ipynb) 
for detailed explanation.  

### Results 
The results are described in the [WASSA 2018 Implicit Emotion Shared Task.pdf](https://github.com/Mengsuper/LING530FA2-Implicit-Emotion-Shared-Task/blob/master/WASSA%202018%20Implicit%20Emotion%20Shared%20Task.pdf)
