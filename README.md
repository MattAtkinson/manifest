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

#### Contents
This repository contains two different manifest files :-

1. creator-kit.xml

    This is the default manifest file. This manifest has repository paths which points to their master branch. Hence it is **NOT** recommended as a stable release.
    
        repo init -u https://github.com/CreatorKit/manifest.git -b master

2. creator-release.xml

    This manifest has repository paths which points to latest stable creator kit project's release.

        repo init -u https://github.com/CreatorKit/manifest.git -b master -m creator-release.xml
    
    Above will build the latest release for you. For building any other release use :-
    
        repo init -u https://github.com/CreatorKit/manifest.git -b <release_tag> -m creator-release.xml
