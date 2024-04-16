# Vision Fundamentals

This repository contains notebooks focusing on fundamental concepts in computer vision, implemented using Python with OpenCV and NumPy libraries. Each notebook provides a detailed guide on a specific topic, including the calculation of essential matrices and matrices for perspective transformation, and camera calibration.

## Notebooks:

1. **Fundamental Matrix Calculation:**
   - This notebook guides you through the calculation of the fundamental matrix, a critical concept in stereo vision and structure-from-motion tasks in computer vision. It covers steps such as loading images, converting to grayscale, extracting key features, matching key features, and finally computing and displaying the fundamental matrix.

2. **Homography Matrix Computation:**
   - Explore the computation of the Homography matrix, essential for tasks like image registration, stitching, and perspective transformation. The notebook provides step-by-step instructions for capturing source and destination points, calculating the Homography matrix, and displaying the transformation.

3. **Camera Calibration:**
   - Learn how to calibrate a camera using a checkerboard pattern and image processing techniques. This notebook walks you through generating a checkerboard pattern, capturing an image, enabling mouse click events for point selection, computing the projection matrix, and concluding with camera calibration.

## How to Use:

1. Clone the repository to your local machine:
   ```
   git clone https://github.com/your-username/Vision-Fundamentals.git
   ```

2. Open and run the desired notebook using Jupyter Notebook or JupyterLab.

3. Follow the step-by-step instructions within each notebook to understand and implement the fundamental concepts in computer vision.

## Dependencies:

- Python 3.x
- OpenCV
- NumPy
- Matplotlib
- Jupyter Notebook or JupyterLab

## License:

This repository is licensed under the MIT License. Feel free to use and modify the code for educational and research purposes.
