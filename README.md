# usb_cam_calibration
Calibration of an usb camera using [usb_cam](http://wiki.ros.org/usb_cam) and [camera_calibration](http://wiki.ros.org/camera_calibration) ROS packages

### To calibrate a camera
```shell
$ roslaunch usb_cam_calibration usb_camera_calibration.launch video_device:="/dev/video1"
```

### To see raw and rectified images after calibration
```shell
$ roslaunch usb_cam_calibration usb_camera_calibrated.launch video_device:="/dev/video1"
```

### Tutorial and references
- http://wiki.ros.org/camera_calibration/Tutorials/MonocularCalibration
- https://docs.opencv.org/2.4/doc/tutorials/calib3d/camera_calibration/camera_calibration.html
- https://docs.opencv.org/2.4/_downloads/pattern.png

