# LiDAR Scanning Outdoor Object Dataset (LSOOD)

This dataset is collected by an HDL-32E Velodyne LiDAR sensor carried by our UGV platform. Raw point clouds collected from a real outdoor scene are segmented into individual obstacles according to a fast spatial clustering method [1]. We developed a semi-automatic 3D object labeling tool to store individual object point clouds [2]. The UGV and a semi-automatic 3D object labeling tool are presented in the following figure. 

&nbsp;
<p float="left">
    <img src="image/Car.jpg"/>
</p>

&nbsp;

&nbsp;
<p float="left">
    <img src="image/Tool1.jpg"/>
</p>

&nbsp;

**Tip:** The result of point cloud experiment usually faces greater randomness than 2D image. We suggest you run your experiment more than one time and select the best result.

&nbsp;
<p float="left">
    <img src="image/Tool2.jpg"/>
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
## Point Cloud Part Segmentation
### Run the training script:

- Full dataset

``` 
python main_partseg.py --exp_name=partseg 
```
