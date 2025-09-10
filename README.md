## Small Underwater Objects 3D Point Cloud Dataset
This repository provides a high-quality underwater Objects 3D point cloud dataset acquired using the BlueView BV5000 S3 multibeam sonar. The dataset includes multiple real underwater objects captured at different distances and labeled for object detection and recognition tasks.

## Overview
The dataset contains 3D point cloud representations of underwater objects such as tires, dummies, drums, and nets. All data were collected in real sea environments using a multibeam sonar scanner and processed to generate .xyz files with intensity values.

- Device: BlueView BV5000 S3
- Environment: Real ocean near Korea Maritime and Ocean University
- Depth: ~6 meters
- Maximum Distance: ~15 meters
- Format: `.xyz`, `.son`, `.txt`, `.pgm`, `.ppm`, `.csv`

## Dataset Structure
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
