aruco_ros
=========
### ROS API

#### Messages

 * aruco_ros/Marker.msg

        Header header
        uint32 id
        geometry_msgs/PoseWithCovariance pose
        float64 confidence

 * aruco_ros/MarkerArray.msg

        Header header
        aruco_ros/Marker[] markers

### Start


 * Start the nodelet
 
    ```
    roslaunch uvc_camera camera_nodelet.launch
    roslaunch aruco_ros aruco_nodelet.launch
    ```

* Start the node
 
    ```
    roslaunch uvc_camera camera_node.launch
    roslaunch aruco_ros aruco_node.launch
    ```





[1]: http://www.sciencedirect.com/science/article/pii/S0031320314000235 "Automatic generation and detection of highly reliable fiducial markers under occlusion by S. Garrido-Jurado and R. Muñoz-Salinas and F.J. Madrid-Cuevas and M.J. Marín-Jiménez 2014"
