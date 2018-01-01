### -1, 2017
- [CNN Is All You Need](http://arxiv.org/abs/1712.09662v1), Qiming Chen, Ren Wu

The Convolution Neural Network (CNN) has demonstrated the unique advantage in
audio, image and text learning; recently it has also challenged Recurrent
Neural Networks (RNNs) with long short-term memory cells (LSTM) in
sequence-to-sequence learning, since the computations involved in CNN are
easily parallelizable whereas those involved in RNN are mostly sequential,
leading to a performance bottleneck. However, unlike RNN, the native CNN lacks
the history sensitivity required for sequence transformation; therefore
enhancing the sequential order awareness, or position-sensitivity, becomes the
key to make CNN the general deep learning model. In this work we introduce an
extended CNN model with strengthen position-sensitivity, called PoseNet. A
notable feature of PoseNet is the asymmetric treatment of position information
in the encoder and the decoder. Experiments shows that PoseNet allows us to
improve the accuracy of CNN based sequence-to-sequence learning significantly,
achieving around 33-36 BLEU scores on the WMT 2014 English-to-German
translation task, and around 44-46 BLEU scores on the English-to-French
translation task.


