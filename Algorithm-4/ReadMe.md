## SIFT Algorithm Implementation

This repository contains a Python implementation of the **Scale-Invariant Feature Transform (SIFT)** algorithm, widely used for feature detection and matching in computer vision tasks such as image recognition and object tracking.

### Features

- **Image Preprocessing**: Converts images to grayscale and ensures float32 format for further processing.
- **Gaussian Pyramid Generation**: Builds multi-scale representations of images using Gaussian filters.
- **Difference of Gaussian (DoG)**: Highlights regions with significant intensity changes to detect keypoints.
- **Keypoint Detection**: Identifies scale- and rotation-invariant keypoints in images.
- **Keypoint Orientation**: Computes gradient orientation and magnitude around each keypoint.
- **Descriptor Computation**: Generates 128-dimensional descriptors for robust matching.
- **Feature Matching**: Matches descriptors between images using Lowe's ratio test.
- **Visualization**: Includes tools for plotting grayscale images and visualizing matched keypoints between image pairs.

### Installation

Ensure the following dependencies are installed:
- Python 3.8+
- NumPy
- Matplotlib
- SciPy
- OpenCV
- Pillow

Install using `pip`:
```bash
pip install numpy matplotlib scipy opencv-python pillow
