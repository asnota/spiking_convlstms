# Spiking convLSTMs
The project proposes a new multimodal dataset seqGraph, comprising semantic, image and audio representations of diatonic harmonic sequences (in C major only). 
The dataset was tested in a generative setting with a custom spiking convLSTM model and shown the best results compared to the models trained with the seqMNIST (custom selection of the MNIST images to form the sequences of digits) and MovingMNIST.
The current stage of the experiment involves the exploitation of the visual data, received out of the sequences of chords represented via the system of graphs. 
The additional dimension introduced via graph representation allowed 2D representation of the initial 1D data and the application of the image data augmentation strategies.

The  <a href="https://openreview.net/forum?id=M24Cs12Gq_A">article</a> describing the experiment will be presented at <a href="https://openreview.net/group?id=AAAI.org/2023/Workshop/creativeAI">The AAAI-23 Workshop on Creative AI Across Modalities</a> on the 13th of February 2023.

The data and the code of this project are available under the MIT licence.

Reference:
```
@inproceedings{
shvets2023spiking,
title={Spiking Conv{LSTM} for Semantic Music Generation},
author={Anna Shvets},
booktitle={The AAAI-23 Workshop on Creative AI Across Modalities},
year={2023},
url={https://openreview.net/forum?id=M24Cs12Gq_A}
}
```

