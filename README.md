## Small Underwater Objects 3D Point Cloud Dataset
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
Tire/
├── Tire_3m/
│   ├── *.xyz   # 3D Point Cloud (x, y, z, intensity)
│   ├── *.txt   # Sonar Setting information
│   └── *.son   # Raw sonar files
│   └── *.metadata
│         └──Tire ()
│            └──images_pgm
│            └──images_ppm
│            └──images_data
│            └──Tire ()_head.txt
│            └──Tire ()_pins.cvs
├── Tire_6m/
│   ├── *.xyz
│   ├── *.txt
│   └── *.son
│   └── *.metadata
│         └──Tire ()
│            └──images_pgm
│            └──images_ppm
│            └──images_data
│            └──Tire ()_head.txt
│            └──Tire ()_pins.cvs
└── Tire_10m/
│   ├── *.xyz
│   ├── *.txt
│   └── *.son
│   └── *.metadata
│         └──Tire ()
│            └──images_pgm
│            └──images_ppm
│            └──images_data
│            └──Tire ()_head.txt
│            └──Tire ()_pins.cvs
│
Dummy/
├── Dummy_3m/
│   ├── *.xyz
│   ├── *.txt
│   └── *.son
│   └── *.metadata
│         └──Dummy ()
│            └──images_pgm
│            └──images_ppm
│            └──images_data
│            └──Dummy ()_head.txt
│            └──Dummy ()_pins.cvs
├── Dummy_6m/
│   ├── *.xyz
│   ├── *.txt
│   └── *.son
└── Dummy_10m/
│   ├── *.xyz
│   ├── *.txt
│   └── *.son
│
Drum/
├── Drum_3m/
│   ├── *.xyz
│   ├── *.txt
│   └── *.son
├── Drum_6m/
│   ├── *.xyz
│   ├── *.txt
│   └── *.son
└── Drum_10m/
    ├── *.xyz
    ├── *.txt
    └── *.son

Net/
├── Net_3m/
│   ├── *.xyz
│   ├── *.txt
│   └── *.son
├── Net_6m/
│   ├── *.xyz
│   ├── *.txt
│   └── *.son
└── Net_10m/
    ├── *.xyz
    ├── *.txt
    └── *.son

Chair/
├── Chair_3m/
│   ├── *.xyz
│   ├── *.txt
│   └── *.son
├── Chair_6m/
│   ├── *.xyz
│   ├── *.txt
│   └── *.son
└── Chair_10m/
    ├── *.xyz
    ├── *.txt
    └── *.son
```
