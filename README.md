# Getting_started_with_LiDAR
Collection of sources to get started with LiDAR processing

# Software tools

To get started with working with Light Detection and Ranging data there are numerous helpful tools and tutorials that will be summarized on this page. The usefulness will somewhat depend on which kind of LiDAR data you are applying and what your objectives are but several of the tools will also work with different datasets and applications.

## Visualization and basic handling of LiDAR data

### CloudCompare

CloudCompare is THE open and free solution for processing point-clouds with a graphical user interface (GUI). You can find a very basic Tutorial to get started here: 

[Cloud Compare Basics Tutorial](https://github.com/fabianfassnacht/CloudCompare_Basics_1/blob/main/1_cloud_compare_basics.md)

Many more resources can be found online.

### FUSION

Another free and open software solution with GUI is FUSION which was developed by the US Forest Service and which can be downloaded here:

[FUSION download](http://forsys.sefs.uw.edu/fusion/fusionlatest.html)

FUSION can be a bit counter-intuitive to work with at the beginning but generally works fine and has nice automatization options using commandline tools and works particularly well with airborne laserscanning data-

### LASTools

LASTools is a commercial software suite with high performance processing option including all important standard processing chains of laserscanning data. Downside is that it not for free. Students of FU Berlin can contact me since we currently have a license for LASTools. You can find LASTools here: [LASTools webpage](https://lastools.github.io/)

### lidR package in R

The lidR package offers a comprehensive set of functions and tools to efficiently process LiDAR data in R - the packages is also very well documented and the most important resources can be found here:

[lidR package webpage](https://r-lidar.github.io/lidRbook/)


## Software solutions and packages to extract individual trees from mobile and terrestrial LiDAR data

### 3DFin

3Dfin is free and open software to extract tree stem positions, height and diameters in multiple heights along the tree stems. It is available as Python package as well as plug-in to CloudCompare (see above). 3DFin works very well for low to medium complexity stands and with some tuning also has reasonable results for comparably complex stands. It is easy to use and implement. You can find a tutorial for the CloudCompare implementation here:

[3DFin tutorial](https://github.com/fabianfassnacht/Cloud_Compare_3DFin/blob/main/1_3Dfin_cloudcompare.md)


### DendRobot

An alternative approach for extract tree stem position and individual tree attributs is DendRoboto - I did not try this software yet but it also looks interesting and can be found here:

[Dendrobot](https://dendrobot.czu.cz/download)

## Ray Cloud Tools

A python package for efficient point cloud processing. Did not try it yet but looks quite promising as well.

[RayCloudTools github page](https://github.com/csiro-robotics/raycloudtools)

## SimpleForest / SimpleTree

Stand-alone software to extract detailed QSM models from dense point clouds (mostly from terrestrial or mobile laserscanning data). Good tutorials are available amongst others in the form of Youtube Videos. You should be able to find all resources here:

[SimpleFoorest webpage](https://simpleforest.org/)





