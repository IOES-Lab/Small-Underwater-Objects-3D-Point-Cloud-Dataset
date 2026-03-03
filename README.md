## Small Underwater Objects 3D Point Cloud (SOUP) Dataset
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.18475883.svg)](https://doi.org/10.5281/zenodo.18475883)

This repository provides a high-quality 3D point cloud dataset of underwater objects acquired using the BlueView BV5000 MK2-1350 mechanical scanning sonar (MSS). This dataset contains 3D point cloud data at various distances and poses, and features multiple labeled real-world underwater objects for object detection and recognition tasks.

## Overview
The SUOP dataset is publicly available and contains 3D point cloud data of tires, dummies, drums, chairs, and nets collected in real marine environments. Each object includes a total of 300 data samples, with corresponding sonar metadata and 2D sonar images provided for each sample.

- Device: BlueView BV5000 MK2-1350
- Environment: Real ocean near Korea Maritime and Ocean University
- Depth: ~6 meters
- Maximum Distance: ~30 meters
- Format: `.xyz`, `.son`, `.txt`, `.pgm`, `.ppm`, `.csv`

## 📁 Dataset Structure
```
SOUP_dataset/
├── chair/
|   ├── chair_range_10m/
|   |   ├── case_001/
|   |   |   ├── metadata/
|   |   |   |   ├── head_info.txt
|   |   |   |   ├── ping_info.csv
|   |   |   |   └── case_settings.txt
|   |   |   ├── ping_data/
|   |   |   |   ├── ping_0/
|   |   |   |   |   ├── range_data.txt
|   |   |   |   |   ├── image.ppm
|   |   |   |   |   └── image.pgm
|   |   |   |   ├── ping_1/
|   |   |   |   |   └── ...
|   |   |   |   └── .../
|   |   |   └── raw_data.son
|   |   |   └── point_cloud.xyz
|   |   ├── case_002/
|   |   |   └── .../
|   |   └── .../
|   ├── chair_range_6m/
|   |   └── ...
|   └── chair_range_3m/
|       └── ...
├── drum/
|   └── ...
├── dummy/
|   └── ...
├── net/
|   └── ...
└── tire/
    └── ...
```
