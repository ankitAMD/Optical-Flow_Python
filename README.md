# Optical-Flow_Python
Optical Flow_Python
..................................................

EROOR  : NO MODULE NAMED VIDEO 

SOLUTION : MAY BE YOU INSTALL OPENCV BUT OPENCV NOT CONTAIN VIDEO MODULE SO INSTALL GITHUB FILE OF OPENCV AND RUN THIS FILE (opt_flow )IN OPENCV/PYTHON/SAMPLE/OPT_FLOW.IPYNB 

link are https://github.com/opencv/opencv. (the link of opencv)

Some readable link: https://medium.com/@anuragranj/how-many-numbers-does-it-take-to-compute-optical-flow-aa9545337b91

https://arxiv.org/pdf/1504.06852.pdf

What is Optical flow ?
Optical flow is the pattern of apparent motion of image objects between two consecutive frames caused by the movemement of object or camera. It is 2D vector field where each vector is a displacement vector showing the movement of points from first frame to second.
                         https://github.com/ankitAMD/Optical-Flow_Python/blob/master/opt_flow.ipynb

It shows a ball moving in 5 consecutive frames. The arrow shows its displacement vector. Optical flow has many applications in areas like :

    Structure from Motion
    Video Compression
    Video Stabilization .
    
 IN CODE WE USE We use the function: cv.calcOpticalFlowFarneback (prev, next, flow, pyrScale, levels, winsize, iterations, polyN, 
 
 polySigma, flags) WHICH MAINLY USE FOR DENSE OPTICAL FLOW
 
https://github.com/ankitAMD/Optical-Flow_Python/blob/master/bbb.png



Basic about code Syntax :
1. np.arctan2 :  Element-wise arc tangent of x1/x2 choosing the quadrant correctly.(Simple in my words it is arc of tangent(roughly  

thinks as tan oppose)).

(https://docs.scipy.org/doc/numpy-1.14.0/reference/generated/numpy.arctan2.html)

2.img.shape : Image properties include number of rows, columns and channels, type of image data, number of pixels etc.

Shape of image is accessed by img.shape. It returns a tuple of number of rows, columns and channels (if image is color)

If image is grayscale, tuple returned contains only number of rows and columns. So it is a good method to check if loaded image is 

grayscale or color image.   (https://docs.opencv.org/3.0-beta/doc/py_tutorials/py_core/py_basic_ops/py_basic_ops.html)

3.numpy.mgrid:  nd_grid instance which returns a dense multi-dimensional “meshgrid”. (https://docs.scipy.org/doc/numpy-1.14.0/reference/generated/numpy.mgrid.html)

4. numpy.vstack:   Stack arrays in sequence vertically (row wise). 

(https://docs.scipy.org/doc/numpy/reference/generated/numpy.vstack.html)

https://www.tutorialspoint.com/numpy/numpy_vstack.htm

5.cv.cvt.Color(img, cv.COLOR_GRAY2BGR) :A method named cvtColor() is used to convert colored images to grayscale.

https://www.tutorialspoint.com/opencv/opencv_colored_images_to_grayscale.htm

6.cv.polylines:draw Polylines on an image using the method polylines() of the imgproc class.  

https://www.tutorialspoint.com/opencv/opencv_drawing_polylines.htm

7.np.zeros :Return a new array of given shape and type, filled with zeros. 
ex:  np.zeros(5)

     array([ 0.,  0.,  0.,  0.,  0.])
     
     np.zeros((5,), dtype=int)

    array([0, 0, 0, 0, 0])

https://docs.scipy.org/doc/numpy/reference/generated/numpy.zeros.html

8.np.unit8 :Unsigned integer (0 to 255)

(https://docs.scipy.org/doc/numpy-1.13.0/user/basics.types.html)

9.np.arange([start, ]stop, [step, ]dtype=None) : Return evenly spaced values within a given interval.

>>> np.arange(3)

array([0, 1, 2])

>>> np.arange(3.0)

array([ 0.,  1.,  2.])

>>> np.arange(3,7)

array([3, 4, 5, 6])

>>> np.arange(3,7,2)

array([3, 5])

https://docs.scipy.org/doc/numpy/reference/generated/numpy.arange.html

10.cv.remap : Use the OpenCV function cv::remap to implement simple remapping routines.

https://docs.opencv.org/3.1.0/d1/da0/tutorial_remap.html(this is best example and see also figure).

http://www.peeknpoke.net/single-post/2016/10/29/OpenCV-remap-function

11. import sys : The sys module provides information about constants, functions and methods of the Python interpreter. dir(system) gives a summary of the available constants, functions and methods. Another possibility is the help() function. Using help(sys) provides valuable detail information.

https://www.python-course.eu/sys_module.php

https://docs.python.org/2/library/sys.html

12.sys.argv : The Python sys module provides access to any command-line arguments via the sys.argv. This serves two purposes −

    sys.argv is the list of command-line arguments.

    len(sys.argv) is the number of command-line arguments.

Here sys.argv[0] is the program ie. script name.

https://www.tutorialspoint.com/python/python_command_line_arguments.htm

13.video.create_capture :n OpenCV, a video can be read either by using the feed from a camera connected to a computer or by 

reading a video file. The first step towards reading a video file is to create a VideoCapture object. Its argument can be either 

the device index or the name of the video file to be read.

https://www.learnopencv.com/read-write-and-display-a-video-using-opencv-cpp-python/

14.cv.imshow ,cam.read() :https://www.learnopencv.com/read-write-and-display-a-video-using-opencv-cpp-python/

http://opencv-python-tutroals.readthedocs.io/en/latest/py_tutorials/py_gui/py_video_display/py_video_display.html

15.prev.copy() :)     Return a shallow copy of x.

https://docs.python.org/2/library/copy.html

16.cv.calcOpticalFlowFarneback: https://docs.opencv.org/2.4/modules/video/doc/motion_analysis_and_object_tracking.html

17.cv.dastroy all windows :

https://techtutorialsx.com/2017/04/30/python-opencv-reading-and-displaying-an-image/
    

18. HSV flow VIsualization :

https://dsp.stackexchange.com/questions/2687/why-do-we-use-the-hsv-colour-space-so-often-in-vision-and-image-processing

https://www.reddit.com/r/opencv/comments/6g298p/understanding_hsv_optical_flow_visualization_with/















































