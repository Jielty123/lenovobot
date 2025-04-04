Workspace for the build of a mobile robot based on a Lenovo roomba.
It uses LdLidar14 (from Lenovo Roomba), KinectV2, KinectV1

## Lidar LdLidar14

- brttly musss deinstalliert sein sonst erkennt er /dev/ttyUSB0 nicht

´´´
sudo apt remove brltty
´´´
- Treiber für cp341 muss installiert sein
- ggf chmod von port ums berechtigung zuzulassen

´´´
sudo chmod 666 /dev/ttyUSB0
´´´

## Kinect V1
https://medium.com/robotics-weekends/how-to-turn-old-kinect-into-a-compact-usb-powered-rgbd-sensor-f23d58e10eb0

- 5V Spannungsversorgung
