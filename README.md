# usb_cam_calibration
Calibration of an usb camera using [usb_cam](http://wiki.ros.org/usb_cam) and [camera_calibration](http://wiki.ros.org/camera_calibration) ROS packages

### Dependencies
```shell
sudo apt-get install ros-melodic-camera-calibration
sudo apt-get install ros-melodic-usb-cam
```

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
- http://wiki.ros.org/image_pipeline/CameraInfo
- https://docs.opencv.org/2.4/_downloads/pattern.png

