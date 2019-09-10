# Introduction

This is the official inplementation of point cloud semantic segmentation.


# Dependencies
- `python` (tested on python2.7)
- `PyTorch` (tested on 0.3.0)
- `cffi`
- `h5py`

# Installation
1. Clone this repository.
2. Compile source codes for slice pooling/unpooling layers by following the readme file in `layers`


# Data Preparation
1. Process the S3DIS dataset by following the readme file in `data`.

# Train
1. Launch training by the command below:
```bash
$ python train.py
```


# License
Codes in this repository are released under MIT License (see LICENSE file for details).




