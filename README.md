### Image Processing with OpenCV

This Python script demonstrates how to process an image using OpenCV, NumPy, and Matplotlib.

#### Installation

Make sure you have the following libraries installed:

- OpenCV
- NumPy
- Matplotlib

You can install them using pip:
```
pip install opencv-python numpy matplotlib
```
Usage

To use the **process_image** function, follow these steps:

1. Import the necessary libraries:
```
import cv2
import numpy as np
import matplotlib.pyplot as plt
```
2. Define the path to your input image.
```
input_image_path = "path_to_your_image.jpg"
```
3. Call the process_image function and store the results in variables.
```
cropped, resized, processed = process_image(input_image_path)
```
4. Customize the image processing parameters in the function as needed.

5. Run the script.

Example
Here's an example of how to use the script with an explanation:

```
input_image_path = "path_to_your_image.jpg"
cropped, resized, processed = process_image(input_image_path)
```
This code will process the input image by cropping, resizing, adjusting brightness and contrast, and applying thresholding. The original and processed images will be displayed using Matplotlib.

You can change the **input_image_path** to the path of your own image for processing.

### Output

The **process_image** function returns the original image and the processed image after cropping, resizing, brightness, contrast, thresholding

![Local Image](https://github.com/Shalu9576/Image_Processing/blob/main/output.png)

### Note

Feel free to customize the image processing parameters in the script to suit your specific requirements.

Enjoy image processing with OpenCV!






