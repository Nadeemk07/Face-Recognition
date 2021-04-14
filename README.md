# Face-Recognition

Face Detection using Python and OpenCV with webcam

OpenCV is a Library which is used to carry out image processing using programming languages like python. 

### Approach/Algorithms used in project:

This project uses LBPH (Local Binary Patterns Histograms) Algorithm to detect faces. It labels the pixels of an image by thresholding the neighborhood of each pixel and considers the result as a binary number.
LBPH uses 4 parameters :
(i) Radius: the radius is used to build the circular local binary pattern and represents the radius around the
central pixel.

(ii) Neighbors : the number of sample points to build the circular local binary pattern.

(iii) Grid X : the number of cells in the horizontal direction.

(iv) Grid Y : the number of cells in the vertical direction.

