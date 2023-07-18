# wamv2023

## Sensor tower 
(ip:192.168.0.32 user:argnctu)

```
Wamv_nycu_description wamv_urdf.launch

velodyne_pointcloud VLP16_points_wamv.launch

lidar_crop lidar_crop.launch
```
## IPC
(ip:192.168.0.30 user:ray)

```
cd duckiepond-nctu 

ipc_run.sh
start_wamv_ipc.sh

ipc_join.sh
bot-proman-deputy
```

## 西風
```
cd duckiepondd-nctu 
roslaunch duckiepond joy_node.launch veh:=/
```

## TVL ip
base tvl 
192.168.0.12

Wamv tvl
192.168.0.22
