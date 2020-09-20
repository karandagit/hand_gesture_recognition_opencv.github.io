# hand_gesture_recognition_opencv.github.io
  This code helps you to understand hand gesture recognition using webcam.
  
## Version 
  python 3 or above is recommended
  
## Commands 
  pip install opencv-python
  pip install numpy
  
## Motion DEtection and Thresholding
  To detect the hand region from the image, we need to threshold the image so that only our hand region becomes visible and all the other unwanted regions are pointed as black. This is what motion detection is all about.
  
## Contour Extraction
  After thresholding the image, we find contours in the resulting image. The contour with the largest area is assumed to be our hand. 
  
