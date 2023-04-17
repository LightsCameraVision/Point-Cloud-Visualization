# Point Cloud Visualization

![Status](https://img.shields.io/static/v1.svg?label=Status&message=Finished&color=green)
   
**Video Tutorial:** 
[![YouTube](https://img.shields.io/static/v1.svg?logo=youtube&label=YouTube&message=Point%20Cloud%20Visualization&color=red)](https://youtu.be/VpyJy0DnWHE)   
**Author:** [Light, Camera, Vision!](https://www.youtube.com/c/LightsCameraVision)

## Setup

**Step 1: (Optional)** If you don't want to mess up your existing setup, consider creating a conda environment.

PPTK works with Python 3.6
```
conda create -n LCV_PC_VIS python=3.6
conda activate LCV_PC_VIS
```

**Step 2: (Required)**
```
pip install -r requirements.txt
```
To read .laz files using laspy in addition to .las files.
```
python3 -m pip install "laspy[lazrs,laszip]"
```

## Data
Please download the data folder from this [link](https://www.dropbox.com/s/t7p9eop2ta1xagz/data.zip?dl=0) and keep it in the main directory as shown below or change the paths in the code. The data references are provided at the end of this repo.
```
│Point-Cloud-Visualization/
├──data/
├──.......
```

## What to Expect?
In this turorial, we learn the easy ways to visualize several different point cloud file formats that are commonly used to store point cloud-type information using two very popular python packages ([Open3D](http://www.open3d.org/) & [pptk - Point Processing Toolkit](https://github.com/heremaps/pptk)).

* The list of file formats covered here is below, with references to the popular datasets they are found in.
  - ply (Toronto3D)
  - pcd (Trimble, Toyota PCD datasets)
  - npz, npy (ScanNet, ShapeNet, Sun RGB-D, A2D2-Audi Autonomous Driving Dataset)
  - hdf5 (ModelNet-C, ShapeNet-C, ScanObjectNN)
  - binary (KITTI)
  - las, laz (USGS 3DEP)
  - txt (ModelNet40, Semantic3D)
  
### Misc Useful Links:
1. [Open3D Shortcut Control Keys](http://open3d.org/html/tutorial/Basic/visualization.html#:~:text=%2D%2D%20Mouse%20view%20control%20%2D%2D)
2. [PPTK Shortcut Control Keys](https://heremaps.github.io/pptk/viewer.html#:~:text=Hot%20keys.,Description)
  
### Data References:
1. PLY file: https://github.com/HuangCongQing/Point-Clouds-Visualization/blob/master/2open3D/data/fragment.ply
2. pcd file: https://github.com/PointCloudLibrary/data/tree/master/terrain
3. ShapeNet: https://shapenet.org/
4. ScanObjectNN: https://hkust-vgd.github.io/scanobjectnn/
5. KITTI data: http://www.cvlibs.net/datasets/kitti/index.php
6. las file: vegetation_1_3.las: https://github.com/laspy/laspy/blob/master/tests/data/vegetation_1_3.las
7. laz file: https://github.com/laspy/laspy/blob/master/tests/data/plane.laz
8. ModelNet40: https://modelnet.cs.princeton.edu/

---

[![Star the repository](https://img.shields.io/static/v1.svg?logo=star&label=⭐&message=Star%20The%20Repository&color=orange)](https://github.com/LightsCameraVision/Point-Cloud-Visualization/)  Feel free to ⭐   this repo if you found this tutorial somewhat helpful. Thanks!   
[![YouTube](https://img.shields.io/static/v1.svg?logo=youtube&label=YouTube&message=Ask%20Questions&color&color=red)](https://youtu.be/VpyJy0DnWHE) If you have any question, please comment on the YouTube video. 

---

<table border="0" width="10%">
  <tr>
    <td><img src="https://img1.github.io/tmp/1.jpg" height="80" width="82"></td>
    <td><img src="https://img1.github.io/tmp/2.jpg" height="80" width="82"></td>
    <td><img src="https://img1.github.io/tmp/3.jpg" height="80" width="82"></td>
  </tr>
  <tr>
    <td><img src="https://img1.github.io/tmp/4.jpg" height="80" width="82"></td>
    <td><img src="https://img.shields.io/github/stars/LightsCameraVision/Point-Cloud-Visualization.svg?style=social"></td>
    <td><img src="https://img1.github.io/tmp/6.jpg" height="82" width="82"></td>
  </tr>
   <tr>
    <td><img src="https://img1.github.io/tmp/7.jpg" height="82" width="82"></td>
    <td><img src="https://img1.github.io/tmp/8.jpg" height="82" width="82"></td>
    <td><img src="https://img1.github.io/tmp/9.jpg" height="82" width="82"></td>
  </tr>
</table>
