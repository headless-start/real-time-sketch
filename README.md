# Real-Time Sketch Generation using Adaptive Thresholding
This Python project demonstrates real-time sketch generation from a webcam feed using OpenCV. The program captures video frames from the camera, processes the frames using various image processing techniques (such as grayscale conversion, Gaussian blur, and Canny edge detection), and generates a sketch-like output.
Features

# Real-time edge detection using Canny Edge Detection.
Adaptive Thresholding applied to the edges to create sketch-like visuals.
Displays live webcam feed with the processed sketch as output.
Press 'q' to exit the application.

#How It Works
Grayscale Conversion: Each frame is first converted into grayscale using cv2.cvtColor(). This reduces the complexity of the image, focusing on intensity.
Gaussian Blur: The grayscale image is then blurred using a Gaussian filter to reduce noise and improve the edge detection process.
Canny Edge Detection: The cv2.Canny() function detects edges in the image based on intensity gradients.
Adaptive Thresholding: Finally, the cv2.adaptiveThreshold() function is used to convert the edges into a binary image, enhancing the sketch effect.

#Usage
Start the application by running the script.
You should see a window displaying the real-time video feed with sketch-like edges drawn on it.
Press 'q' to quit the application and close the window.
