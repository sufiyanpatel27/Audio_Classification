# Audio_Classification

## Dataset

dataset is taken from [urbansound8K](https://urbansounddataset.weebly.com/download-urbansound8k.html). this dataset have approximately 8000 audio samples of 10 classes

* air_conditioner 
* street_music
* engine_idling
* children_playing
* drilling
* jackhammer
* dog_bark
* siren
* car_horn
* gun_shot  

## preprocessing

we are using [librosa](https://pypi.org/project/librosa/) for reading the audio data. also we need other liberaries like

* numpy
* pandas
* sklearn
* keras

## Training

we are using keras to build our neural network from scratch

## model

finally we are saving the best model as hdf5 format.
