## Viola-Jones Face Detection

This repository provides both a custom implementation and a built-in OpenCV-based implementation of the **Viola-Jones face detection algorithm**, which is widely used in real-time face detection applications.

### Features

#### Custom Implementation
- **Integral Image**: Efficient feature computation using integral images.
- **Haar-like Features**: Multiple feature types, including horizontal, vertical, and square configurations.
- **Weak Classifiers**: Basic classifiers for specific face regions like eyes, nose, and mouth.
- **Cascade Architecture**: Two-stage cascade for detecting facial features.
- **Non-Maximum Suppression**: Removes overlapping face detections.

#### Built-in Implementation
- **Pre-trained Classifier**: Uses OpenCV's Haar Cascade pre-trained models.
- **Face Detection**: Fast and accurate face detection with minimal setup.
- **Visualization**: Highlights detected faces in an image with bounding boxes.

### Installation

Ensure you have Python 3.8+ and the following libraries installed:
- OpenCV
- NumPy
- Matplotlib
- tqdm

Install dependencies using `pip`:
```bash
pip install opencv-python numpy matplotlib tqdm
