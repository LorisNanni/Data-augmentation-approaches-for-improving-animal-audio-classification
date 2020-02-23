# Data-augmentation-approaches-for-improving-animal-audio-classification
Data augmentation approaches for improving animal audio classification

The code for the data augmentation approaches is here: Data augmentation approaches for improving animal audio classification

Moreover, we have tested the offical matlab toolbox for audio data augmentation in the following way:
augmenter = audioDataAugmenter( ...
    "AugmentationMode","sequential", ...
    "AugmentationParameterSource","random", ...
    "NumAugmentations",10);
% https://it.mathworks.com/help/audio/ref/audiodataaugmenter.html

data = augment(augmenter,audioIn,fs); %Augment the original signal  audioIn

As CNN we have use matlab pretrained CNN, see: https://it.mathworks.com/help/deeplearning/ug/pretrained-convolutional-neural-networks.html
