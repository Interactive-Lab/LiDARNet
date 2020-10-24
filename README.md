# LiDAR Scanning Outdoor Object Dataset (LSOOD)

This dataset is collected by an HDL-32E Velodyne LiDAR sensor carried by our UGV platform. Raw point clouds collected from a real outdoor scene are segmented into individual obstacles according to a fast spatial clustering method [1]. We developed a semi-automatic 3D object labeling tool to store individual object point clouds [2]. The UGV and a semi-automatic 3D object labeling tool are presented in the following figure. 

&nbsp;
<p float="left">
    <img width="300" height="150" src="images/Car.jpg"/>
    <img width="300" height="150" src="images/Tool1.png"/>
</p>

&nbsp;

&nbsp;
<p float="left">
    <img width="300" height="150" src="images/Tool1.png"/>
</p>

&nbsp;

**Tip:** The result of point cloud experiment usually faces greater randomness than 2D image. We suggest you run your experiment more than one time and select the best result.

&nbsp;
<p float="left">
    <img width="150" height="150" src="images/Tool2.png"/>
</p>

&nbsp;

## LSOOD:
Train&Testing sample statistic

|  | Mean Class Acc | Overall Acc | 
| :---: | :---: | :---: | 
| Train | 90.2 | 92.9 |
| Test | 90.9 | 93.3 |
| Total | 90.7 | 93.5 |

&nbsp;
## PCitation
### If you find our work useful in your research, please consider citing:

1.	Y Tian, W Song, L Chen, et al., A Fast Spatial Clustering Method for Sparse LiDAR Point Clouds Using GPU Programming, Sensors 20 (8), 2309
2.	W Song, L Zhang, Y Tian, et al., CNN-based 3D object classification using Hough space of LiDAR point clouds, Human-centric Computing and Information Sciences 10 (1), 1-14
