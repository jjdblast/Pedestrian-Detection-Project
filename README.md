# Pedestrian-Detection-Project



#Project Goal:

The goal of this project is to explore how better feature representation and various visual cues can be used to improve detection quality in computer vision area.

Specifically, this project targets the fascinating and meaningful real world problem "pedestrian detection" as a test case. Using current state of the art pedestrian detector ["SquaresChnFtrs"](https://bitbucket.org/rodrigob/doppia) as a baseline, I am using two methods to increase detection accuracy. Expand 10 HOG+LUV channels into 20 channels by using DCT (discrete cosine transform); Encode the optical flow using SDt features (image difference between current frame T and coarsely aligned T-4 and T-8); 


Note that this project is largely to reproduce observations/discovery in [“Benenson etc., 2014 EECV” paper](http://rodrigob.github.io/documents/2014_eccvw_ten_years_of_pedestrian_detection_with_supplementary_material.pdf). On the basis of the baseline detector, the DCT method is expected to have 3.53% improvement, and the optical flow method is expected to have 4.47% improvement. 



#What Has Been Done:

The project started in mid-November 2014, up to now, below is achieved::

1. Got the baseline detector up and running
2. Got baseline  miss rate
3. Implemented the new baseline + DCT pedestrian detector. 
5. Cross verified that DCT algorithm CUDA implementation in the new detector is correct. [Codes here](https://github.com/LevinJ/DCT-Algorithm-Verification-Cuda-)


#What's Next:

Implement the baseline + optical flow 

#Current Major Issues:
Refer [here](https://github.com/LevinJ/Pedestrian-Detection-Project/issues) for a complete list of issues and corresponding updates in this project.

#Project video and paper:
Video: [here](http://youtu.be/jGV0zTtxmmA)

Paper: will be uploaded soon.
