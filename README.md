# cnn-sound-classifier

An application of convolutional neural networks (CNN) using Tensorflow Keras API. The purpose of the project is to classify the sounds of steps of two different people using CNNs, which doesn't sound very intuitive since CNNs are commonly used for image processing. The idea of this implementation is to use spectrograms of audio dataset, since spectrograms are images which can be better suited for training CNNs.
![persona1_train_frames094](https://user-images.githubusercontent.com/34671846/215186820-98f86128-da31-466e-9cb1-0759b547b61f.png)

The image above corresponds to the spectrogram of a 2 second audio of a person's steps.

After training the convolutional network for 6 epochs, the accuracy of the sound classifier went from 55.07% at the start, to 75.17% after the training was done.

 - _espectrograms.zip_ contains a zipfile with 752 spectrograms for class1 (steps of a person) and 716 spectrograms for class2 (steps of another person), which are splitted in code in a 80% train, 10% validation and 10% test ratio. 
 - _cnn_stepsound_classifier.ipynb_ is a jupyter notebook which contains the implementation of the CNN sound classifier.

