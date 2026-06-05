# Canny-Edge-Detection-using-OpenCV

## Overview

This project demonstrates the implementation of the Canny Edge Detection algorithm using Python and OpenCV. Canny Edge Detection is a widely used image processing technique for identifying object boundaries and significant intensity changes in an image.

## Objectives

- Load and process a sample image.
- Convert the image to grayscale.
- Apply the Canny Edge Detection algorithm.
- Visualize and analyze the detected edges.
- Study the impact of different threshold parameters on edge detection results.

## Technologies Used

- Python
- OpenCV
- NumPy
- Matplotlib
- Jupyter Notebook


## Algorithm

1. Read the input image.
2. Convert the image to grayscale.
3. Apply Gaussian filtering to reduce noise.
4. Compute image gradients.
5. Perform non-maximum suppression.
6. Apply double thresholding.
7. Track edges using hysteresis.
8. Display the detected edges.


## Applications

- Object Detection
- Image Segmentation
- Medical Image Analysis
- Autonomous Vehicles
- Computer Vision Systems
- Pattern Recognition

## Requirements

```bash
pip install opencv-python numpy matplotlib
```

## Running the Project

1. Clone the repository:

```bash
git clone https://github.com/your-username/canny-edge-detection-opencv.git
```

2. Open Jupyter Notebook:

```bash
jupyter notebook
```

3. Run:

```bash
CANNY EDGE DETECTION.ipynb
```

## Conclusion

The Canny Edge Detection algorithm effectively detects object boundaries and important image features. The quality of edge detection depends on the selected threshold values, making parameter tuning an essential part of image processing applications.

## Author

**Dinesh Karthik R**

## License

This project is licensed under the MIT License.
