# Heart-Sound-Classification-CinC
Classification Normal and Abnormal Heart PCG Signal

### Install

This project requires **Python 3** and the following Python libraries installed:

- [Keras](http://www.keras.io/)
- [Tensorflow](http://tensorflow.org/)
- [Numpy](http://numpy.org/)
- [Scipy](http://scipy.org/)
- [Matplotlib](https://matplotlib.org/)





You will also need to have software installed to run and execute a [Jupyter Notebook](http://ipython.org/notebook.html)

You could just install [Anaconda](http://continuum.io/downloads) distribution of Python, which already has the above packages and more included. 


### Run

In a terminal or command window, navigate to the top-level project directory  (that contains this README) and run one of the following commands:

```bash
ipython notebook HB\HB_Bidirectional_lstm.ipynb
```  

This will open the Jupyter Notebook software and project file in your browser.


## Data

The heartbeat recording can be downloaded from [here](https://physionet.org/physiobank/database/challenge/2016/). The dataset contains about 3500 recording.


## About

The focus of this project is to classify whether the patient has “normal” or “abnormal” heart sound from the Phonocardiogram (PCG) or heartbeat recordings to quickly identify patients who would require further diagnosis.  This is a supervised learning problem since we already know if the heart sound in training dataset is normal or abnormal. The basic idea is to convert each heart sound recording(wav file) to fft signal and normalize it and apply bidirectional LSTM algorithm to classify heart sound.

The dataset used for this capstone is available freely as part of the PhysioNet / Computing in Cardiology Challenge 2016 which focuses on automatic classification of normal / abnormal phonocardiogram (PCG) recording. Along with clean heart sounds, the dataset also contains some noisy recordings. The samples have been obtained from both normal subjects and pathological patients, providing a variety of signal sources

