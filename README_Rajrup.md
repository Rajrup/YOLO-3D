# YOLO-3D

## Overview

This is a 3D object detection and tracking system that uses YOLOv11 and Depth Anything v2.

## Install dependencies

```bash
# CUDA 11.8
conda create -n yolo-3d python=3.10
conda activate yolo-3d
pip install -r requirements.txt
```

## Run the code

```bash
# Changed the source video path in the run.py file
python run.py
```

## Output

The output will be saved in the `output.mp4` file.