# libuvc_camera_parameters
This repository is for stock of uvc_camera parameters with launch files.  

## Setup the permission of the camera device file.  
See [this page](http://wiki.ros.org/libuvc_camera) and create a rule file.  
The camera vender ID is "15aa".  

## Preparing.  
    $ sudo apt install ros-kinetic-libuvc-camera  
    $ cd libuvc_camera_parameters  
    $ catkin_make  
    $ source devel/setup.bash
    $ roslaunch my_libuvc_camera KYT_camera.launch  
    
