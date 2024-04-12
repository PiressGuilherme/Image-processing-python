# Image-processing-python

This Python code uses the pandas, numpy, cv2 (OpenCV), skimage (scikit-image), and matplotlib libraries to process and display images. Here's a step-by-step description of the code:

Library Imports: The necessary libraries are imported, including pandas for data manipulation, numpy for numerical operations, cv2 for image processing, skimage for loading images, and matplotlib for image display.

DataFrame Creation: A fictional DataFrame is created to store information about the images, including the patient ID and the image path.

process_image Function: This function takes the path of an image, loads it using OpenCV, converts it to grayscale, and inverts its colors. It then returns a pd.Series object containing the processed and inverted images.

Applying the Function to the DataFrame: The process_image function is applied to each row of the DataFrame using the apply method, and the results are added as new columns to the DataFrame.

Image Visualization: A loop iterates over each row of the DataFrame, loads the original, processed, and inverted images, and displays them in three side-by-side subplots using matplotlib.

Displaying the Images: The images are displayed in three subplots: the original image, the processed image (in grayscale), and the inverted image (with inverted colors).

This code is a simple example of how to load, process, and visualize images in Python using popular image processing and data analysis libraries.
