# Lane Detection Using Canny Hough Estimation of Vanishing Points (CHEVP)
## Example result
![example](https://github.com/KaiXin-Chen/Lane-Detection-Using-Canny-Hough-Estimation-of-Vanishing-Points/blob/main/Image_for_readme.png)
## Basic info
This is a class project for Stanford CS231A, which detects the direction of a lane. This is a reimplementation of the closed source project "Lane detection and tracking using B-Snake" by Yue Wang, Eam Khwang Teoha, Dinggang Shen. We first reimplemented CHEVP with aid from OpenCV functions (cv2.houghP() and cv2.Canny()), then we reimplemented the OpenCV functions we used as well (reimplemented cv2.houghP() and cv2.Canny()). 
## Contributors 
Contributors are Kaixin Chen and Shunyao Xu. Kaixin Chen is incharge of the CHEVP algorithm used for lane detection, parameter tunning and a RANSAC function used by CHEVP. Shunyao Xu is incharge of implementing Hough transform and Canny edge detector used by CHEVP (these two functions basically serve the same purpose as cv2.HoughP() and cv2.canny()), parameter tunning and evaluation. 
## How to use
Run the Lane_Detection_Through_Spline jupyter notebooks to perform lane detection. 
## Want to lern more?
Read Final Report.pdf for more information about the project
