# LiDAR
This is a showcase repository for a CMake project which applies filteration, segmentation, and clustering. The point cloud data used is generated by a LiDAR mounted on top a car in a road scene. The C++ code is using custom functions and the PCL library to detect objects. 


The project can be seperated into three parts, filteration, segmentation and clustering.
- In filteration, point cloud is downed sampled and cropped to the area of focus.
- In segmentation, a RANSAC algorithm is used for road segmentation.
- In clustering, Kd-tree along with euledian clustering algorithm is applied.


Final Result

![alt text](https://video.udacity-data.com/topher/2019/March/5c85992d_pcdstreamdetection/pcdstreamdetection.gif)

