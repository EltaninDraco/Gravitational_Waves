# Gravitational Waves

## Introduction
Gravitational waves are ripples in spacetime caused by some of the most violent and energetic processes in the Universe. 
This project aims to analyze spectrogram images generated from the strain data of LIGO detectors to identify gravitational wave events using Convolutional Neural Networks (CNNs).

## Dataset
The dataset used in this project is sourced from the LIGO Open Science Center (LOSC). We use the strain data from two LIGO detectors:

* Hanford (H1)
* Livingston (L1)

Example files used:

- `H-H1_GWOSC_4KHZ_R1-1126259447-32.hdf5`
- `L-L1_GWOSC_4KHZ_R1-1126259447-32.hdf5`

## Project structure

gravitational-wave-CNN
* data
> H-H1_GWOSC_4KHZ_R1-1126259447-32.hdf5
> L-L1_GWOSC_4KHZ_R1-1126259447-32.hdf5
* spectrograms
> - spectrogram_H1.png
> - spectrogram_L1.png
* notebooks
 > - 01_generate_spectrograms.ipynb
 > - 02_train_model.ipynb
 > - 03_evaluate_model.ipynb
* src
 > - create_spectrogram.py
 > - train_model.py
 > - evaluate_model.py
* README.md
> requirements.txt

## Installation
To get started, clone this repository and install the required dependencies:

`git clone https://github.com/EltaninDraco/gravitational-wave-analysis.git`

`cd gravitational-wave-analysis`

`pip install -r requirements.txt`


## Acknowledgements
This project use data from the LIGO Open Science Center. 
Special thanks to the LIGO Scientific Collaboration for making their data publicly available.
