# ROS_vision

ดูเลขตำแหน่งกล้อง

$ ls /dev/video*

ติดตั้ง Opencv_apps

$ sudo apt-get install ros-noetic-opencv-apps
<http://wiki.ros.org/opencv_apps>

การติดตั้ง กล้อง USB ใน ROS


$ sudo apt-get install ros-noetic-usb-cam

เรียกฉายภาพ

$ roslaunch usb_cam usb_cam-test.launch

การเรียกใช้ Face Detection

$ roslaunch opencv_apps face_detection.launch 

แก้ไฟล์ launch ตั้งค่า OpenCV version

$ sudo gedit face_detection.launch 

