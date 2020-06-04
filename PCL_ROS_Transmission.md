PCL与ROS之间的数据转换
=========
1.PointCloud与sensor_msgs::LaserScan的转换
-------------
* 
2.pcl::PointCloud::Ptr 和Pcl::PointCloud两个类的相互转换
-------------
* Ptr类型和非Ptr类型相互转换\
`
pcl::PointCloud<pcl::PointXYZ>::Ptr cloud_Ptr(new pcl::PointCloud<pcl::PointXYZ>);<br>
pcl::PointCloud<pcl::PointXYZ> cloud;<br>
cloud=*cloud_Ptr;<br>
cloud_Ptr=cloud.makeShared;
`
* Ptr类型和非Ptr类型相互转换
