# HSV Range Finder Tool

This tool will help you to extract the HSV codes from any images with manual adjustments.

This script allows users to manually find the optimal HSV (Hue, Saturation, Value) range for image processing tasks using OpenCV. By adjusting trackbars in real time, users can tune the minimum and maximum HSV values and observe how the image changes based on their selections. This is particularly useful for color segmentation, object detection, or thresholding based on specific color ranges.

Features; Adjustable trackbars for real-time tuning of HSV values. Displays the selected HSV range in the console. Uses bitwise operations to display a masked output image based on the current HSV range. Resizeable window and image to ensure compatibility with most screen sizes. Easy integration with other image processing tasks.

How to Use; Clone or download this repository. Replace your data path here in the script with the path to your desired image. Run the script in your Python environment. Use the trackbars to adjust the HSV min/max values. The image will update in real time based on your selections. The console will display the current HSV range values, which can be used in further image processing tasks. Press 'q' to exit the program.

Requirements; Python 3.x OpenCV Numpy

You can install the dependencies via pip: pip install opencv-python numpy

Example Usage; Once you run the script, an image will open with six trackbars corresponding to the Hue, Saturation, and Value ranges (min and max for each). As you adjust these values, the output image will dynamically display the parts of the image that fall within the selected HSV range. This tool is useful for determining the right HSV thresholds for tasks like object detection or color-based segmentation.

Example output from the console: (hMin = 35, sMin = 50, vMin = 100), (hMax = 85, sMax = 255, vMax = 255)

License This project is licensed under the MIT License.
