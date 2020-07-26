# SampleRNN-colab

This is a slightly modified version of [Tensorflow implementation of SampleRNN](https://github.com/Unisound/SampleRNN) to be run in Google Colaboratory using Google Drive as data storage. See [the original repository](https://github.com/Unisound/SampleRNN) for details.

## Modifications

- Added `--output_dir` argument, allowing you to specify a path where generated WAV files are saved. 
- Leading zeros to filenames of generated WAV files (02 comes before 10 for any possible post-processing of files).
- 44.1 kHz sample rate and other default settings
- Updates on deprecated code.

## Run in Google Colaboratory
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/olaviinha/SampleRNN-colab/blob/master/SampleRNN.ipynb)
