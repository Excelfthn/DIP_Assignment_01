# Digital Image Processing Assignment 01
This project is part of a Digital Image Processing assignment in Google Colab. The program demonstrates downsampling and upsampling techniques on a sample image using Python, OpenCV, NumPy, and Matplotlib.

# Steps
1. Generates a 10×10 random black-and-white image.
2. Converts the image to grayscale for easier processing.
3. Applies downsampling with three methods:
      - Average pooling
      - Max pooling
      - Median pooling
4. Applies upsampling with three interpolation methods:
      - Nearest Neighbor
      - Bilinear
      - Bicubic
5. Show the processed pixel values and visualizes the results for comparison.

# Downsampling Methods
  - Average Pooling: Replaces each block with the average of its pixels, creating a smoother and less detailed result.
  - Max Pooling: Takes the maximum pixel value in each block, preserving the strongest or brightest eatures.
  - Median Pooling: Uses the median pixel value in each block, reducing noise and producing a more balanced result.

# Upsampling Methods
  - Nearest Neighbor: Copies the closest pixel value, producing a blocky but fast result.
  - Bilinear: Uses the weighted average of 4 neighboring pixels, giving smoother but slightly blurred results.
  - Bicubic: Uses 16 neighboring pixels with cubic interpolation, resulting in the smoothest and most detailed output.

# Summary
This code shows how different downsampling and upsampling methods affect image quality. Pooling methods simplify the image differently, between smooth, sharp and balanced. While interpolation methods reconstruct the image with varying levels of smoothness and detail.

