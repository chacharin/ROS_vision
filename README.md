# ROS_vision

ดูเลขตำแหน่งกล้อง

$ ls /dev/video*

ติดตั้ง Opencv_apps

$ sudo apt-get install ros-noetic-opencv-apps
//<http://wiki.ros.org/opencv_apps>

การติดตั้ง กล้อง USB ใน ROS

$ sudo apt-get install ros-noetic-usb-cam

แก้ไฟล์ launch ตั้งค่า การอ่านภาพ

$ sudo gedit usb_cam-test.launch
ปรับ video_device // io_method // pixel_format // <http://wiki.ros.org/usb_cam>

เรียกฉายภาพ

$ roslaunch usb_cam usb_cam-test.launch

การเรียกใช้ Face Detection

$ roslaunch opencv_apps face_detection.launch 

แก้ไฟล์ launch ตั้งค่า OpenCV version

$ sudo gedit face_detection.launch 

