# Speech-Commands-to-Text
<p align="center">
  <img src = "https://images.hothardware.com/static/newsimages/Item22658/nuance-ditech-main.jpg">
</p>
***

An acoustic wave is a continuous signal. Sampled at a certain rate it becomes a discrete series, a timeseries. And just like a time series, an acustic wave has or doesn't have patterns. And where there are patterns, we have a great pattern feature extractor: a Convolutional Neural Network (CNN). We'll be using the feature extraction capabilities of the CNN to extract the patterns from a sound wave and to map the features of that sound wave to the command/label class they belong to. The process is anologous with extracting features from a picture and then assigning the picture to the class cat, dog, mule, bird, cow.


We'll be using the dataset TensorFlow Speech Commands Dataset which can be found here: http://download.tensorflow.org/data/speech_commands_v0.01.tar.gz


We'll be using LibROSA package to process the audio signals: conda install -c conda-forge librosa
We'll be training a one dimensional CNN on the training and validation sets then we'll be using the testing set to make predictions and to assess the performance of the model
