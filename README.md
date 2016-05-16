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
├── constrained-os
│   └── contiki
├── dist
│   ├── openwrt
│   ├── openwrt-ckt-feeds
|   |       ├── awalwm2m
|   |       ├── button-gateway
|   |       ├── device-manager
|   |       ├── libflow-ex
|   |       ├── libflow
|   |       └── webscripts
│   └── openwrt-feeds
|   |       ├── cgilua
|   |       └── fping
└── packages
    ├── AwaLWM2M
    ├── button-gateway
    ├── button-sensor
    ├── device-manager
    ├── led-actuator
    ├── libobjects
    └── webscripts
```
