# Tornado Infrasound Signal Processing

Python-based signal processing and prediction of tornado infrasound recordings for Time Difference of Arrival (TDOA) analysis.

## Overview

This project analyses three infrasound microphone recordings to improve the detection and localisation of tornado-related signals.

The processing focuses on the expected **1–8 Hz tornado infrasound frequency range** while preserving the relative timing between microphones required for TDOA analysis.

## Methods

The project includes:

* Time-domain and frequency-domain signal analysis
* Cross-correlation and TDOA analysis
* IIR Butterworth band-pass filtering
* FIR band-pass filtering
* PCA-based filtering
* Discrete Wavelet Transform (DWT) filtering
* Autoregressive (AR) prediction
* Kalman filtering and prediction
* Quantitative performance comparison using MAE, RMSE, bias and correlation

## Technologies

* Python
* NumPy
* Pandas
* SciPy
* Matplotlib
* Statsmodels
* PyWavelets
* Jupyter Notebook

## Files

`Tornado_Infrasound_Signal_Processing.ipynb`
Contains the complete signal-processing, filtering, prediction and evaluation workflow.

## Dataset

The original infrasound CSV datasets used for the analysis are not included in this repository.

The notebook was developed using three microphone recordings:

* `Tornado_east.csv`
* `Tornado_north.csv`
* `Tornado_west.csv`

## Purpose

This project was completed as part of university Signal Theory coursework and demonstrates practical application of digital signal processing, Python programming, data analysis and engineering problem-solving.

## Author

**Roedine van der Merwe**
B.Eng Computer & Electronic Engineering
