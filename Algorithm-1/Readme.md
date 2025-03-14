# Grayscale Image Encoding with Padding and 8-Connectivity

This repository contains an implementation of a computer vision task focused on encoding grayscale images using an 8-connectivity pattern. The task includes adding one-pixel padding to the image and encoding pixel values based on their differences with neighboring pixels.

## Key Features

- **Grayscale Image Handling**: Reads and visualizes a grayscale image.
- **Padding Addition**: Adds one-pixel padding to the image by duplicating border pixels.
- **8-Connectivity Encoding**: Encodes pixel values using a binary pattern derived from the intensity differences with their 8-connected neighbors.
- **Modified Encoding**: An alternative encoding approach that adjusts pixel values based on absolute differences.

## Implementation Details

- **Image Padding**: The grayscale image is padded to handle boundary conditions during encoding.
- **Binary Pattern Calculation**: For each pixel, a binary string is generated based on the intensity differences with its neighbors, which is then converted to a decimal value.
- **Visualization**: The original, padded, and encoded images are visualized for comparison.

## Usage

1. Ensure the required dependencies (`numpy`, `matplotlib`, `PIL`) are installed.
2. Run the script to process the input image (`Image-1.png`) and visualize the results.

## Group Members

- Syed Sarib Naveed (NIM-BSCS-2021-41)
- Musawar Hamad Khan (NIM-BSCS-2021-40)
