
# Lane Detection
This code performs lane detection on a given image, identifying left and right lanes using various image processing techniques.

## Description

The script employs the following steps:

1. **Grayscale Conversion**: The input image is converted to grayscale.
2. **Thresholding**: A global threshold based on grayscale intensity is applied.
3. **Region of Interest (ROI) Masking**: A region of interest is defined, masking out the unnecessary parts of the image.
4. **Edge Detection**: Canny edge detection is applied.
5. **Hough Line Transformation**: Detects lines in the image.
6. **Line Extrapolation**: The detected lines are extrapolated to identify the full extent of the lanes.

The final output is an annotated image with the detected lanes highlighted.

## How to Use

1. Update the path to the input image in the script.
2. Run the script to visualize the steps and get the final output.
3. The output will be saved as 'Lane1-image.jpg'.

Note: Adjust parameters as needed based on the input image for optimal results.

---
