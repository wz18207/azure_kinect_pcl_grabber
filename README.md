# Azure_kinect_pcl_grabber

Get point cloud data from Azure Kinect DK by using PCL(point cloud library)
Writing the work based on the Kinect2Grabber by UnaNancyOwen

# Environment

* Visual Studio 2017(or later)
* Azure Kinect Sensor SDK v1.4.1(or later) 
* Point Cloud Library v1.9.1
* .NET Core SDK 3.1.2(or later)

# License

Copyright © 2020 Zhaoyang Wang
Distributed under the [MIT License](http://www.opensource.org/licenses/mit-license.php).

# Contact

* Zhaoyang Wang
  - https://github.com/wz18207
  - wz18207@gmail.com
  - ww02082345@yahoo.com

# Reference

* openni_grabber | Point Cloud Library

  https://github.com/PointCloudLibrary

* Azure Kinect Sensor SDK API Reference | GitHub.io

  https://microsoft.github.io/Azure-Kinect-Sensor-SDK/develop/index.html

# ToDoList

* Collect the point cloud data into *.pcd .
* Save Body Tracking Data in a file different from *.pcd.
* Save Body Tracking and pcl::PointXYZRGBA into *.pcd.