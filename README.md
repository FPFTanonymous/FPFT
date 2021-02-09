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

Stock is a new public data we release; it consists of the daily historical stock prices of FANG, 
the four American technology companies Facebook, Amazon, Netflix, and Google.
We collected closing prices adjusted for stock splits, from 2017-01-03 to 2021-01-08.
[Urban sound](https://urbansounddataset.weebly.com/urbansound8k.html) and 
[Air condition](https://archive.ics.uci.edu/ml/datasets/Appliances+energy+prediction) datasets are also available
[here](https://drive.google.com/file/d/1aw5G48bqxTUnsUILau8tejCrBH1I8nXX/view?usp=sharing).
