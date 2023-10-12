# Video Processing - Movement Detection and Counting
A python script that can detect cars moving in the video and count the number of moving objects. This is the prototype of my final coursework project, I used the basis of the detection system shown in this python script and created a full-fledged [Camera Surveillance System](https://github.com/RoninSanta/CM3070-Camera-Surveillance-System-Project).

### [Background]
This script uses frame differencing and background subtraction techniques to detect and label cars on the 'Main Street'. Frame differencing involves comparing two video frames and identifying any changes in pixels. Background subtraction involves identifying moving objects by comparing the current frame and ref frame.

### [Open-CV]
This library is the `KEY` for object detection and analysis, it is an important open-source computer vision it can be used to detect and recognize faces, identify objects, classify human actions in videos, track camera movements, track moving objects etc...


### [Highlight Objects]
After applying the final function, I use the cv2 library to detect contours and draw bounding rectangles around objects that meet a certain area threshold (>2500). This helps to avoid tagging bicycles and pedestrians.


[Before] ![before](https://github.com/RoninSanta/VideoProcessing-MovementDetect_and_Counting/assets/109457795/c450e39b-826d-4f62-9147-3f1e0d168bd1)

[After] ![after](https://github.com/RoninSanta/VideoProcessing-MovementDetect_and_Counting/assets/109457795/e183f962-0245-443d-8448-5a1cac132f13)
