# Audio Signal Processing and Machine Learning Tasks

A collection of audio signal processing and machine learning exercises focused on feature extraction, speech analysis, and audio classification.

These projects explore fundamental concepts in digital audio processing using Python libraries such as NumPy, SciPy, scikit-learn, and Matplotlib.

---

# Project Overview

The repository contains two practical assignments related to audio analysis and classification:

* **E01** → Audio feature extraction and basic signal analysis
* **E02** → Spectrogram analysis and MFCC-based audio classification

The exercises combine theoretical concepts and practical implementations commonly used in:

* Speech recognition
* Audio classification
* Digital signal processing
* Machine learning systems

---

# Topics Covered

## Exercise 01 — Audio Features and Signal Analysis

Main topics:

* Audio loading and visualization
* Signal playback and waveform analysis
* Feature extraction
* Zero-Crossing Rate (ZCR)
* Signal energy computation
* Signal duration analysis
* Feature normalization
* Audio classification using machine learning

---

### Key Concepts

#### Audio Signals

Audio signals are represented as:

* One-dimensional arrays
* Amplitude values sampled over time

The project analyzes audio recordings sampled at fixed frequencies.

---

#### Waveform Visualization

The exercises include:

* Plotting audio waveforms
* Inspecting amplitude variations
* Understanding temporal signal behavior

Waveform analysis helps identify patterns and characteristics of speech signals.

---

#### Zero-Crossing Rate (ZCR)

The Zero-Crossing Rate measures:

* How frequently the signal changes sign
* The number of crossings through zero amplitude

ZCR is commonly used in:

* Speech detection
* Music analysis
* Audio segmentation

---

#### Signal Energy

Energy estimation evaluates:

* Signal intensity
* Overall amplitude power

This feature is useful for:

* Detecting speech activity
* Distinguishing silence from active audio

---

#### Feature Combination

Different combinations of features are tested, including:

| Combination | Features              |
| ----------- | --------------------- |
| Combo 1     | Energy, Duration, ZCR |
| Combo 2     | Energy and ZCR        |
| Combo 3     | Duration and ZCR      |

The goal is to evaluate how different feature sets affect classification performance.

---

#### Machine Learning Classification

The project applies machine learning techniques using:

* Support Vector Machines (SVM)
* Feature normalization
* Training and testing datasets

Classification models are trained to recognize and distinguish audio patterns.

---

## Exercise 02 — Spectrograms and MFCC Features

This exercise focuses on advanced audio feature extraction techniques commonly used in speech and audio recognition systems.

Main topics:

* Spectrogram generation
* Frequency-domain analysis
* MFCC feature extraction
* Audio preprocessing
* Classification using extracted features

---

### Spectrogram Analysis

A spectrogram represents:

* Frequency content over time
* Signal intensity at different frequencies

It provides a visual representation of how audio signals evolve.

---

### MFCC — Mel Frequency Cepstral Coefficients

MFCCs are among the most widely used features in speech recognition.

They model how humans perceive sound frequencies using the Mel scale.

MFCC extraction involves:

* Fourier Transform
* Mel filter banks
* Logarithmic scaling
* Cepstral analysis

---

### Why MFCCs Are Important

MFCCs are extensively used in:

* Speech recognition systems
* Speaker identification
* Voice assistants
* Audio classification

because they efficiently capture perceptually relevant sound characteristics.

---

### Frequency-Domain Processing

The project explores the transition from:

* Time-domain representation

to:

* Frequency-domain representation

allowing deeper analysis of speech and audio signals.

---

# Libraries and Tools

## Exercise 01

* NumPy
* SciPy
* Matplotlib
* scikit-learn
* IPython Display

## Exercise 02

* NumPy
* SciPy
* Matplotlib
* scikit-learn
* Audio feature extraction libraries

---

# Skills Developed

The exercises help develop practical knowledge in:

* Digital signal processing
* Audio feature engineering
* Speech analysis
* Machine learning workflows
* Data preprocessing
* Feature extraction techniques
* Audio classification systems
