# Image-Handling-and-Pixel-Transformations-Using-OpenCV
## AIM:
Write a Python program using OpenCV that performs the following tasks:

Read and Display an Image.
Adjust the brightness of an image.
Modify the image contrast.
Generate a third image using bitwise operations.
## Software Required:
Anaconda - Python 3.7
Jupyter Notebook (for interactive development and execution)
## Algorithm:
### Step 1:
Load an image from your local directory and display it.

### Step 2:
Create a matrix of ones (with data type float64) to adjust brightness.

### Step 3:
Create brighter and darker images by adding and subtracting the matrix from the original image.
Display the original, brighter, and darker images.

### Step 4:
Modify the image contrast by creating two higher contrast images using scaling factors of 1.1 and 1.2 (without overflow fix).
Display the original, lower contrast, and higher contrast images.

### Step 5:
Split the image (boy.jpg) into B, G, R components and display the channels

Program Developed By:
Name: S. Devi

Register Number: 212225100008

## program
### Step1:
- Load an image from your local directory and display it.
### step2:
- Draw a line from the top-left to the bottom-right of the image.

- Draw a circle at the center of the image. 

- Draw a rectangle around a specific region of interest in the image. 

- Add the text "OpenCV Drawing" at the top-left corner of the image.

- Draw a line from the top-left to the bottom-right of the image
### Step3:
- Convert the image from RGB to HSV and display it.
    
- Convert the image from RGB to GRAY and display it. 

- Convert the image from RGB to YCrCb and display it. 
    
- Convert the HSV image back to RGB and display it.
  
### Step4:
- Access and print the value of the pixel at coordinates (100, 100). 

- Modify the color of the pixel at (200, 200) to white.
  
### Step5:
- Resize the original image to half its size and display it.
  
### Step6:
- Crop a region of interest (ROI) from the image (e.g., a 100x100 pixel area starting at (50, 50)) and display it.

### Step7:
- Flip the original image horizontally and display it. 

- Flip the original image vertically and display it.

### Step8:
- Save the final modified image to your local directory.
