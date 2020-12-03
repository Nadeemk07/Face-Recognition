# Face-Recognition

Face Detection using Python and OpenCV with webcam

OpenCV is a Library which is used to carry out image processing using programming languages like python. This project utilizes OpenCV Library to make a Real-Time Face Detection using your webcam as a primary camera.

### Approach/Algorithms used:

This project uses LBPH (Local Binary Patterns Histograms) Algorithm to detect faces. It labels the pixels of an image by thresholding the neighborhood of each pixel and considers the result as a binary number.
LBPH uses 4 parameters :
(i) Radius: the radius is used to build the circular local binary pattern and represents the radius around the
central pixel.

(ii) Neighbors : the number of sample points to build the circular local binary pattern.

(iii) Grid X : the number of cells in the horizontal direction.

(iv) Grid Y : the number of cells in the vertical direction.

The model built is trained with the faces with tag given to them, and later on, the machine is given a test data and machine decides the correct label for it.
