# Task 3 : Social Distancing Detector 

**Description:**
Implement a real time Social Distancing detector which can identify the distance between two individuals in a crowd.

**Implementation:**

The script runs on videos of mp4 format. This can however be changed in the code and even real time analysis can be done via a camera.

The method adapted for distance calculation is calculating the centroid of rectangle on persons identified thorugh YOLOv3-tiny and then eucledian distance is calculated between these centroids.

For Successfully running this script you need "Yolov3-tiny.weights" file in the same folder as the script.
The weights file can be downloaded [Here](https://pjreddie.com/media/files/yolov3-tiny.weights "YOLOv3-tiny Weights file")
