<h1 align="center"> <p> THU-Wildfire </p></h1>
<p align="justify">
We introduce THU-Wildfire, the first integrated dataset of multitemporal and multimodal observations from four wildfire events. It combines high-precision photogrammetry and 3D point cloud reconstruction before and after fires, continuous visible-light, thermal infrared, and LiDAR monitoring during fire events, time-series records of pollutant concentrations (PM2.5, CO, etc.) and meteorological parameters (wind speed, temperature, humidity, etc.), as well as fine-grained geospatial data on forest structure (tree species, canopy cover, etc.).
</p>

<img src="media/teaser.jpg" alt="Intro" style="zoom:100%" >

## 🚗Download
**Please fill out this [form](https://docs.google.com/forms/d/e/1FAIpQLScydu7G5nZO5ayeeiqmlQ8ibHu5O4VBuN8V4qvV8LEaV54pkQ/viewform?usp=sharing&ouid=118271888753834723056) to get the download link.**

## 🆕 News
* Our paper is accepted by **EMS**🎉!
* 2025-05-22: Data of *Ninuo* region has been released!
* 2025-05-16: The subset of THU-Wildfire will be released soon 😊!

## 🔢Data Structure

```
Region name
├── Pre-fire&Post-fire
│    ├── Pre-fire
│    │    ├── LiDAR
│    │    │    └── Pointcloud.las
|    |    └── Photogrammetry
│    │         ├── DSM.tif
│    │         └── Orthophoto.tif
│    └── Post-fire
│         └── ...
│       
├── Pollutant&Weather
│    ├── Station1.csv
│    ├── Station2.csv
│    └── ...
│
└── Active-fire
     ├── Image
     │    ├── Annotation
     │    │    ├── 000016.png    
     │    │    └── ...
     │    ├── InfraredJPG
     │    │    ├── 000001.jpg
     │    │    └── ...
     │    ├── Optical
     │    │    ├── 000001.jpg
     │    │    └── ...  
     │    ├── Optical_projected
     │    │    ├── 000001.tif
     │    │    └── ...      
     │    ├── ThermalTIFF
     │    │    ├── 000001.tif
     │    │    └── ...       
     |    └── ThermalTIFF_projected
     │         ├── 000001.tif
     │         └── ...
     └── Video
          └── ...
```

* Please note that all geographic coordinates have been offset.
* For the complete video file, please contact me to obtain it.
* Detailed technical parameters will be disclosed in our future paper.