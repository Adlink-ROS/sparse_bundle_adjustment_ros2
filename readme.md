# Sparse Bundle Adjustment Library (ROS 2.0)  
This is ROS 2.0 version pkg for Sparse Bundle Adjustment Library (needed for slam_karto_ros2)  
The original repo (ROS 1.0) was developed at Willow Garage as part of the vslam stack.  

## Developer  
* HaoChih, LIN (haochih.lin@adlinktech.com)  

## License  
BSD License (adhere from original ROS 1.0 sparse_bundle_adjustment pkg)  
  
## Compile (examples)      
$ cd ~/ros2_ws  
$ ament build --only-packages sparse_bundle_adjustment  

For isolated build  
$ ament build --isolated --build-tests --symlink-install --only sparse_bundle_adjustment  

## As libraries in other ROS 2.0 pkg  
Add "find_package(sparse_bundle_adjustment REQUIRED)" in your CMakeLists.txt   
