# Image Management and Computer Vision Tasks

A collection of image processing and computer vision exercises focused on color management, image compression, feature extraction, homography estimation, and image stitching.

These projects explores fundamental concepts in digital imaging using Python libraries such as OpenCV and scikit-image.

---

# Project Overview

The repository contains two practical image management assignments:

- **E03** → Image processing and color space management
- **E04** → Feature extraction, homography estimation, and image stitching

The tasks cover both theoretical concepts and practical implementations commonly used in computer vision and multimedia systems.

---

# Topics Covered

## Exercise 03 — Image Processing and Color Management

Main topics:

- RGB image loading and visualization
- Grayscale conversion
- Color space transformations
- YCbCr color representation
- Chroma compression
- Gaussian filtering
- Image reconstruction

### Key Concepts

#### RGB Images

Images are represented using:

- Red channel
- Green channel
- Blue channel

Each pixel is defined by the intensity combination of the three channels.

---

#### Grayscale Images

Conversion from RGB to grayscale reduces the image to:

- One intensity channel
- Values between black and white

This simplifies image analysis and reduces computational complexity.

---

#### YCbCr Color Space

The project explores conversion from RGB to YCbCr:

| Channel | Description |
|---|---|
| Y | Luminance (brightness) |
| Cb | Blue chrominance |
| Cr | Red chrominance |

This color model is widely used in:

- JPEG compression
- Video encoding
- Multimedia systems

---

#### Chroma Compression

The project implements chroma compression by:

- Blurring Cb and Cr channels
- Preserving luminance details

Gaussian filtering with different sigma values is tested to analyze:

- Compression quality
- Visual degradation
- Color preservation

---

## Exercise 04 — Feature Matching and Homography

This exercise focuses on geometric computer vision techniques.

Main topics:

* SIFT keypoint extraction
* Feature matching
* Homography estimation
* Perspective warping
* Image stitching

---

### Keypoint Extraction

Features are extracted using:

#### SIFT (Scale-Invariant Feature Transform)

SIFT detects:

* Corners
* Edges
* Distinctive local patterns

while remaining robust to:

* Scale changes
* Rotation
* Illumination differences

---

### Feature Matching

Descriptors between two images are matched using:

#### Brute Force Matcher (BFMatcher)

Matches are ranked according to descriptor distance.

The project visualizes:

* All matches
* Best 20 matches

to evaluate correspondence quality.

---

### Homography Estimation

A homography matrix is computed to estimate the geometric transformation between two images.

The transformation includes:

* Rotation
* Translation
* Scaling
* Perspective correction

This enables alignment between multiple views of the same scene.

---

### Perspective Warping

Using the computed homography:

* One image is warped
* Images are aligned together

This represents the foundation of:

* Panorama generation
* Image registration
* Image stitching systems

---

## Libraries and Tools

### Exercise 03

* NumPy
* Matplotlib
* scikit-image

### Exercise 04

* OpenCV
* NumPy
* Matplotlib
