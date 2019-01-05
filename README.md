## Advanced Lane Finding
[![Udacity - Self-Driving Car NanoDegree](https://s3.amazonaws.com/udacity-sdc/github/shield-carnd.svg)](http://www.udacity.com/drive)

The goal of this project is to write software pipeline to identify the lane boundaries in a video fram from a front-facing camera. The steps involved are:

* Camera calibration: compute the camera matrix and distortion coefficients.
* Develop a pipeline for lane finding in single images.
* Develop a pipeline for lane finding in video.
*
The different individual steps and the whole pipeline, discussion and tests can be found in the P2.ipynb.

The different folders contain the following:
/output_images/: output images from the different tests using different filters (sobelx, sobely, magnitude and direction gradient, saturation filter) and the different tests images.
/camera_cal/: different chessboard calibration images used for the camera calibration.
/test_images/: images used for testing the pipeline.
/test_videos_output/: the videos processed with the pipeline of line detection for this project.
