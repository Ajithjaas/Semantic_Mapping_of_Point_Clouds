# Sexy Semantic Mapping - RBE549 Homework 2

The following commands have to be run in the terminal to install all the libraries required to run the code.
```json
sudo pip install glob
sudo pip install mxnet
sudo pip install gluoncv
sudo pip install open3d
```

## Semantically Segmeneted Images:
<p align="center">
  <img src="../Outputs/Semantic_Segmentation.gif" width="512">
</p>

## Run the following code in the terminal to initiate Point Cloud painting and ICP:
Next we have to go the below location in the terminal:
```json
.../Code/
```
RBG Image:
<p align="center">
  <img src="../Outputs/Images/rgb_image.png" width="512">
</p>

Corresponding Raw Point Cloud:
<p align="center">
  <img src="../Outputs/Images/pcd_pers.png" width="512">
</p>

For point cloud painting using RGB image:
```json
python main.py --flag = 1
```
<p align="center">
  <img src="../Outputs/Images/rgbpcd_pers.png" width="512">
</p>

For point cloud painting using Segmented image:
```json
python main.py --flag = 0
```
<p align="center">
  <img src="../Outputs/Images/sempcd_pers.png" width="512">
</p>


## To visualize the point clouds results
Next we have to go the below location in the terminal:
```json
.../Outputs/
```
Open the visualize.py file and replace the file name you want to open. Then run the following code in the terminal:
```json
python visualize.py
```

The ICP semantic Point Cloud:
<p align="center">
  <img src="../Outputs/Images/finalpcd.png" width="512">
</p>



