# Lidar-Camera Projection
This code is used to explain the post [here](https://medium.com/@daryl.tanyj/camera-lidar-projection-navigating-between-2d-and-3d-911c78167a94).

## Dependency Installation
Assuming you have installed anaconda. Get all dependencies with
```
conda create --name projection python=3.8 -y
conda activate projection
pip install -r requirements.txt
```

## How to use
```
python lidar_camera_project.py
```

#### Image 3D boxes
![diagram](./assets/1.png)

#### Lidar Points Image
![diagram](./assets/2.png)

#### Lidar 3D boxes
![diagram](./assets/3.png)
