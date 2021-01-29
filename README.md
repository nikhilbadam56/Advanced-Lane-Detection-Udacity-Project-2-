## Advanced Lane Finding

The Project
---

The goals of this project are the following:

* Compute the camera calibration matrix and distortion coefficients given a set of chessboard images.
* Apply a distortion correction to raw images.
* Use color transforms, gradients, etc., to create a thresholded binary image.
* Apply a perspective transform to rectify binary image ("birds-eye view").
* Detect lane pixels and fit to find the lane boundary.
* Determine the curvature of the lane and vehicle position with respect to center.
* Warp the detected lane boundaries back onto the original image.
* Output visual display of the lane boundaries and numerical estimation of lane curvature and vehicle position.

The images for camera calibration are stored in the folder called `camera_cal`.  The images in `test_images` are for testing your pipeline on single frames.

(The complete procedure for the project is being included in the WriteUp.pdf file of this repository.)

## Camera Calibration :
   
   ### Original Image
   
   ![](https://github.com/nikhilbadam56/Advanced-Lane-Detection-Udacity-Project-2-/blob/master/output_images/calibration/originalimage.jpg)
   
   ### Calibrated Image
   
   ![](https://github.com/nikhilbadam56/Advanced-Lane-Detection-Udacity-Project-2-/blob/master/output_images/calibration/calibratedimage.jpg)
   

## Region of interest

  ### Original Image
  
  ![](https://github.com/nikhilbadam56/Advanced-Lane-Detection-Udacity-Project-2-/blob/master/output_images/PerspectiveTransform/car_original.jpg)
  
  
  ### Region oF Interest
  
  ![](https://github.com/nikhilbadam56/Advanced-Lane-Detection-Udacity-Project-2-/blob/master/output_images/PerspectiveTransform/car_roi_overlay.jpg)
  

## Perspective Transform

  ### Perspective Transform
  
  ![](https://github.com/nikhilbadam56/Advanced-Lane-Detection-Udacity-Project-2-/blob/master/output_images/PerspectiveTransform/laneregionperspectivetransform.jpg)

## Polyline Fit(Regression)
 
  ![](https://github.com/nikhilbadam56/Advanced-Lane-Detection-Udacity-Project-2-/blob/master/output_images/Lanepolylinefit/polylinefit2.jpg)

The final output of this project is shown in the below image , you can see that this algorithm performs in detecting lane lines that are curvy , and also giving information about the average radius of curvature of the lane , this can also be used to calculate the steering angle .


![](https://github.com/nikhilbadam56/Advanced-Lane-Detection-Udacity-Project-2-/blob/master/output_images/Final_image.jpg?raw=true)
