# e2box_imu_9dofv4
E2BOX IMU 9DOF V4 ros package

Default baudrate : 115200
Default port : /dev/ttyUSB0

## udev rules
```bash
$ roscd e2box_imu
$ sudo cp e2box_imu.rules /etc/udev/rules.d/
$ sudo service udev restart
```

