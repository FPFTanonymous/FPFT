# FPFT

This project is a C++ implementation of *Fast and Accurate Partial Fourier Transform for Time Series Data* (submitted to KDD21).

## Prerequisites

The implementation requires the following libraries.

- mkl.h
- mkl_dfti.h
- ipp.h
- ipps.h
- fftw3.h

## Datasets

The four datasets used in our paper are available [here](https://drive.google.com/file/d/1ArejxayJdkCTitxhY42iVCCTNpDIc2yd/view?usp=sharing).
They include synthetic random vectors of length of integer power of two.
[Urban sound](https://urbansounddataset.weebly.com/urbansound8k.html) contains 4347 sound recordings in urban environment,
and [Air condition](https://archive.ics.uci.edu/ml/datasets/Appliances+energy+prediction) is composed of 29 time-series vectors of air condition information (e.g., temperature and humidity).
Stock is a new public data we release; it consists of the daily historical stock prices of FANG, 
the four American technology companies Facebook, Amazon, Netflix, and Google.
We collected closing prices adjusted for stock splits, from 2017-01-03 to 2021-01-08.

