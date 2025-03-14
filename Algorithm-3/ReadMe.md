# Harris Corner Detection and Filters

This repository contains an implementation of multiple computer vision techniques, including synthetic image creation, applying gradient-based filters, and detecting corners using the Harris Corner Detection algorithm. These implementations are designed for experimentation and visualization in the field of computer vision.

## Key Features

### 1. Synthetic Image Creation
- Creates a grayscale image with a white background and a centered black box.
- The image dimensions and black box size are customizable.

### 2. Gradient Filters
- **Horizontal Filter**: Detects horizontal edges using a convolution filter `[-1, 0, 1]`.
- **Vertical Filter**: Detects vertical edges using the transpose of the horizontal filter.
- Filters are applied using 2D convolution, and results are normalized for visualization.

### 3. Harris Corner Detection
- Computes the Harris corner response using image gradients.
- Identifies and visualizes the strongest corners in the image.
- Applies non-maximum suppression to highlight distinct corners.
- Displays the top 4 corner points with their coordinates and response values.

## Visualization
- Generates and saves the following outputs:
  - Original grayscale image.
  - Images with horizontal and vertical gradients.
  - Harris corner response visualization with a heatmap.
  - Overlay of the top 4 corners on the original image with labels.

## Requirements
- Python 3.6+
- Required Libraries: `numpy`, `matplotlib`, `Pillow`, `scipy`, `os`, `random`
