# ImageProcessing_
Implement a custom adaptive filter based on local statistics

An image processing exercise notebook focused on noise analysis and adaptive filtering. It demonstrates how to inspect local intensity distributions, apply built-in denoising methods, and implement a custom adaptive filter based on local statistics.

## Overview

This notebook is organized as a practical exercise set centered on **Question 4** with parts **A, B, and C**. It works with a noisy grayscale image and explores how different filtering approaches affect image quality.

The notebook includes:

- loading and displaying a noisy image
- cropping a local region and analyzing its histogram
- applying OpenCV’s bilateral filter
- implementing a custom adaptive filter using local mean and variance
- comparing built-in and hand-written denoising methods

## Features

- **Noisy Image Analysis**  
  Loads a grayscale noisy image and visualizes it.

- **Local Histogram Inspection**  
  Examines the intensity distribution of a cropped image strip.

- **Bilateral Filtering**  
  Applies an edge-preserving smoothing filter.

- **Custom Adaptive Filtering**  
  Implements a local-statistics-based adaptive denoising method.

- **Visual Comparison**  
  Displays the results of both built-in and custom filtering approaches.

## Technologies Used

- Python
- OpenCV (`cv2`)
- NumPy
- Matplotlib

## Libraries Used
```python
import cv2
import numpy as np
import matplotlib.pyplot as plt
