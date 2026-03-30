# Audio Signal Filtering Project
## Project Description

This project is about removing noise from an audio signal using Python.
The goal is to take a noisy audio file and make it clean using signal processing methods.
It shows how to work with signals in time and frequency domain.

## Problem This Project Solves

In real life, audio signals often have noise.
Noise can come from the environment or recording tools.
This makes the audio hard to understand or use.
This project shows how to filter out the noise and improve audio quality.

## What I Did
Loaded an audio file in Python using librosa.
Added artificial noise to the audio to simulate a real noisy signal.
Visualized the original and noisy signals in time domain using plots.
Used FFT (Fast Fourier Transform) to see the frequency content of the signals.
Designed a low-pass Butterworth filter to remove high-frequency noise.
Applied the filter to the noisy signal and saved the filtered audio.
Plotted the filtered audio in time and frequency domains to compare results.
Played original, noisy, and filtered audio in Colab.

## Tools and Libraries Used
Python 3
numpy – numerical calculations and FFT
scipy – signal processing and filter design
matplotlib – plotting signals
librosa – reading audio files and displaying audio
IPython.display.Audio – playing audio in Colab

## What I Learned
How to read and process audio signals in Python.
How to add noise to a signal for testing.
How to use time and frequency domain analysis.
How to design and apply filters to improve signal quality.
How to visualize signal changes with plots.
How to use Google Colab for signal processing projects.

##  How to Run
Upload your audio file to Google Colab.
Run the Python notebook step by step.
Listen to original, noisy, and filtered audio.
Check plots to see how filtering works.
