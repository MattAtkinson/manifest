# Manifest

Manifest for cloning creator kit repositories.

#### Steps for cloning could be:
- mkdir local_dir_name
- cd local_dir_name
- repo init -u https://github.com/CreatorKit/manifest.git -b branch_name
- repo sync

After above steps, your directory structure would be like:
```
.
├── build
|── tools
|   └── creator-docker
├── constrained-os
│   └── contiki
├── dist
│   ├── openwrt
│   ├── openwrt-ckt-feeds
|   |       ├── button-led-controller
|   |       ├── motion-led-controller
|   |       └── relay-gateway
│   └── openwrt-feeds
|   |       ├── awalwm2m
|   |       ├── board-test
|   |       ├── ca8210
|   |       ├── fping
|   |       ├── glog
|   |       ├── proddata
|   |       ├── totd
|   |       └── u-boot
└── packages
    ├── AwaLWM2M
    ├── button-sensor
    ├── motion-sensor
    ├── button-led-controller
    ├── motion-led-controller
    ├── relay-gateway
    └── libobjects
```
