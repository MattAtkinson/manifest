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
|   |       ├── device-manager
|   |       ├── button-led-controller
|   |       └── webscripts
│   └── openwrt-feeds
|   |       ├── awalwm2m
|   |       ├── ca8210
|   |       ├── cgilua
|   |       ├── click-apps
|   |       ├── fping
|   |       └── u-boot
└── packages
    ├── AwaLWM2M
    ├── button-sensor
    ├── motion-sensor
    ├── device-manager
    ├── button-led-controller
    ├── motion-led-controller
    ├── libobjects
    └── webscripts
```
