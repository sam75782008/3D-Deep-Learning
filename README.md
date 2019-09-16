# 3D-Deep-Learning
- This work has been done within 3 months internship at Bentley Systems, Watertown, CT.
- The objective is to provide a pipeline that use 3D lidar data to classify seismic vulnerable buildings for city resilience.
- Over 1,000,000,000+ point clouds of Santa Monica have been utilized to train Point-Cloud classification and segmentation through PointNet.
- The point-cloud datasets are classified as Soft-Story or Non-Soft-Story point, and the classification accuracy as well as intersection of union are utilized (IoU) to evaluate the trained PointNet.
- The sensitivity analysis has been done to obtain the best model, and over 90% accuracy and IoU are achieved.
- For engineering purpose, clustering methods are applied to compute the centroids of predicted points so that the GIS of the soft-story buildings' centroids can further direct to the addresses.  

<div align=center><img width="800" height="400" src="https://github.com/sam75782008/3D-Deep-Learning/blob/master/Images/Data_Preparation.JPG"/></div>
