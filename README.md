#**Pencil Sketch Generator using OpenCV and Matplotlib ::**

This project demonstrates how to transform a color image into a pencil sketch using Python, OpenCV, and Matplotlib. The process involves image preprocessing steps such as grayscale conversion, inversion, blurring, and blending, culminating in a visually appealing pencil sketch effect.

#**Features::**

Read and Display Original Image::
Load the input image from the specified file path.
Display the original image using Matplotlib.

Grayscale Conversion::
Convert the original RGB image into a grayscale image.
Grayscale images are easier to manipulate for artistic transformations.

Image Inversion::
Invert the grayscale image to prepare it for blending operations.

Blurring::
Apply Gaussian blur to the inverted image to create a smooth base for blending.

Pencil Sketch Effect::
Use a custom blending function (dodge_blend) to combine the grayscale image and the blurred inverted image, producing the pencil sketch effect.

Side-by-Side Visualization::
Display the original image and the final pencil sketch side-by-side for comparison.


Code Workflow:

Import Required Libraries::
cv2 for image processing.
matplotlib.pyplot for displaying images.

Read the Input Image::
Load the image from the specified path and convert it from BGR (OpenCV format) to RGB (Matplotlib format).

Step-by-Step Transformation:

Step 1: Display the original image.

Step 2: Convert the image to grayscale.

Step 3: Invert the grayscale image.

Step 4: Apply Gaussian blur to the inverted image.

Custom Blending Function:
Use the cv2.divide() function to create the pencil sketch effect by blending the grayscale image with the blurred image.

Final Output::
Display the original image and the pencil sketch side-by-side using Matplotlib.

Requirements::

Python 3.x

Libraries:

opencv-python

matplotlib

Key Concepts Demonstrated:: 

Image Processing:
Learn how to read, manipulate, and display images using OpenCV.

Matplotlib Visualization:
Visualize intermediate and final results with clear titles and layouts.

Artistic Transformation:
Apply a sequence of operations to achieve a visually appealing pencil sketch effect.

Custom Blending:
Understand how blending techniques can create new visual effects.
