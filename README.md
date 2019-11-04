# Canny-Edge-Detector
The Canny edge detector is an edge detection operator that uses a multi-stage algorithm to detect a wide range of edges in images.
It an image processing method used to detect edges in an image
while suppressing noise.It extracts useful structural information from different vision
objects and dramatically reduce the amount of data to be processed. It has been widely
applied in various computer vision systems. Canny has found that the requirements for
the application of edge detection on diverse vision systems are relatively similar.
<br/>
<br/>
### It involves following steps :
## 1. Noise reduction
## 2. Gradient calculation
## 3. Non-maximum suppression
## 4. Double threshold
## 5. Edge Tracking by Hysteresis

It is also known as the optimal edge detector :
1. The first criterion should have low error rate and filter out unwanted information while
the useful information preserve.
2. The second criterion is to keep the lower variation as possible between the original
image and the processed image.
3. Third criterion removes multiple responses to an edge.
<br/>
<br/>
First of all convert the image to gray-scale. Perform a Gaussian blur on the image.The
gradients can be determined by using a Sobel filter. The image magnitude produced results
in thick edges. Ideally, the final image should have thin edges. Thus, we must
perform non maximum suppression to thin out the edges.After that I performed an edge
tracking algorithm to remove weak edges. Weak edges that are connected to strong edges
will be actual/real edges. Weak edges that are not connected to strong edges will be removed.
I performed this using DFS technique.
<br/>
<br/>
Refer the pdf file for all the algorithms implemented
<br/>
Refer the link for more details : https://iitmcvg.github.io/summer_school/Session3/  
