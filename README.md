# libuvc_camera_parameters
This repository is for stock of uvc_camera parameters with launch files.  

## Setup the permission of the camera device file.  
See [this page](http://wiki.ros.org/libuvc_camera) and create a rule file.  
And find a sampmle command to make a rule file in each launch file header.

## Preparing.  
    $ sudo apt install ros-notetic-libuvc-camera  
    $ mkdir -p ws_libuvc_camera/src  
    $ cd ws_libuvc_camera/src  
    $ git clone https://github.com/m-shimizu/libuvc_camera_parameters  
    $ cd ..  
    $ catkin_make  
    $ source devel/setup.bash  
    $ roslaunch my_libuvc_camera KYT_camera.launch  
    
