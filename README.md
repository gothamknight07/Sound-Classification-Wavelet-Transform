# Sound-Classification-Wavelet-Transform


## Definition

This project classifies sound signals from different environmental classes in the ESC-10 dataset. the above photo summarizes the model steps: <br/>
1. The model read all the signals of different classes and assign a label number to each class.
2. The  signal is converted from the time domain to Wavelet Transform. PCA technique is used to reduce dimensions of wavelet transform as it contain a lot of dimensions.
3. Full Convolutional Neural Network(CNN) is defined and used to classify 10 different classes of ESC-10 dataset.


### install this libraries:
- numpy
- keras
- matplotlib
- librosa
- pylab
- glob
- tensorflow
- scipy
- pywt
