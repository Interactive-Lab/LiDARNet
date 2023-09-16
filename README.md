# LiDARNet v1

This dataset is collected by an HDL-32E Velodyne LiDAR sensor carried by our UGV platform. Raw point clouds collected from a real outdoor scene are segmented into individual obstacles according to a fast spatial clustering method. We developed a semi-automatic 3D object labeling tool to store individual object point clouds. The UGV and a semi-automatic 3D object labeling tool are presented in the following figure. 

&nbsp;
<p float="left">
    <img width="500" height="300" src="images/Car.jpg"/>

</p>
&nbsp;
<p float="left">
    <img width="500" height="300" src="images/Tool1.png"/>
</p>
&nbsp;

**We collected 1056 obstacles from several thousands of scanning frames, containing 4 kinds of common types. All the point coordinates are stored in .csv files with their original and after-centralized x, y, z coordinates.**

&nbsp;
<p float="left">
    <img width="500" height="300" src="images/Tool2.png"/>
</p>

&nbsp;

## LiDAR:
### Train&Testing sample statistic

|       | Building | Bush | Pedestrian | Tree | Total |
| :---: | :---:    |:---: |      :---: |:---: | :---: |
| Train | 180 | 110 | 50 | 190 | 530 |
| Test  | 155 | 113 | 33 | 225 | 526 |
| Total | 335 | 223 | 83 | 415 | 1056 |

&nbsp;
## Citation
### If you find our work useful in your research, please consider citing:

1.	Wei Song*, Dechao Li, Su Sun, Xinghui Xu and Guidong Zu*, Registration for 3-D LiDAR Datasets using Pyramid Reference Object, IEEE Transactions on Instrumentation and Measurement, doi: 10.1109/TIM.2023.3300410, 2023.08.
2.	Wei Song, Zhen Liu, Ying Guo, Su Sun, Guidong Zu, and Maozhen Li, DGPolarNet: Dynamic Graph Convolution Network for LiDAR Point Cloud Semantic Segmentation on Polar BEV, Remote Sensing, Vol.14, No.13: 3825. 2022, https://doi.org/10.3390/rs14153825
3.	Wei Song, Dechao Li, Su Sun, Lingfeng Zhang, Yu Xin, Yunsick Sung, and Ryong Choi, 2D&3DHNet for 3D Object Classification in LiDAR Point Cloud, Remote Sensing, Vol.14, No.13: 3146. 2022, https://doi.org/10.3390/rs14133146

&nbsp;
## Principal Investigator
Wei Song (sw@ncut.edu.cn)

&nbsp;

