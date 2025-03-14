# Histogram of Oriented Gradients (HOG) Implementation

This repository contains an implementation of the Histogram of Oriented Gradients (HOG) algorithm for feature extraction from images. The algorithm is widely used in computer vision applications such as object detection and recognition.

## Features

- **Image Preprocessing**: 
  - Resize images to a standard size (64x128 pixels).
  - Convert images to grayscale for simplified processing.
  
- **Gradient Computation**:
  - Compute gradients in the x and y directions using Sobel filters.
  - Calculate gradient magnitude and direction for each pixel.

- **HOG Feature Extraction**:
  - Divide the image into cells (e.g., 8x8 pixels).
  - Compute histograms of gradient directions within each cell.
  - Normalize blocks of cells to ensure illumination and contrast invariance.
  - Concatenate normalized histograms to form a high-dimensional feature vector.

- **Visualization**:
  - Visualize HOG features as gradient patterns superimposed on the image.

- **Built-in HOG Validation**:
  - Compare the custom implementation with the built-in HOG function from the `skimage.feature` library.

## Requirements

- Python 3.6+
- Required Libraries: `numpy`, `matplotlib`, `Pillow`, `cv2`, `skimage`
