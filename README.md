# Color Detection of Images using OpenCV & python
We’ll start by importing our necessary libraries.
(NumPy for numerical processing, cv2 for our OpenCV bindings, and matplotlib for displaying the images)

next, we need to read the images into a variable and check the read image
(an image that is read is not the original image because by default OpenCV reads the images in BGR format)

Converting read image from BGR format to RGB format

similarly, Converting RGB to HSV format because its easier to classify in HSV format

Setting the threshold values for respective colors to be detected
(any value in between this range will be displayed & other parts will be discarded)

Display the result, as this is not the final result, its the detected image is masked
using bitwise_and operation, we'll display the final result (Detecting the green color in the image)
