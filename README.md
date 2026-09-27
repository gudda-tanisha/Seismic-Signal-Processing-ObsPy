# Seismic Signal Processing & Waveform Analysis in Python

This repository contains a Python-based processing pipeline for real seismic waveform data using ObsPy, NumPy, and Matplotlib.

## Processing Steps
1. Data Ingestion: Automated retrieval of broadband seismic traces via FDSN web services (IRIS client).
2. Signal Conditioning: Baseline drift removal using linear detrending and de-meaning.
3. Tapering & Filtering: Applied cosine tapering to suppress edge artifacts, followed by zero-phase Butterworth bandpass filtering (0.05 Hz – 2.0 Hz).
4. Spectral Analysis: Time-frequency spectrogram generation using Short-Time Fourier Transform (STFT).

## Output Visualization
![Seismic Trace and Spectrogram](seismic_processing_output.png)
