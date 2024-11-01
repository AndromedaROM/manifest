# Platform manifest for Andromeda Android ROM
based on LineageOS

## Getting started

Initialize the manifest
```
repo init --partial-clone -b fifteen -u https://github.com/AndromedaROM/platform_manifest --git-lfs
```

Sync it up
```
repo sync -c -j$(nproc)
```

## Building

Set up the environment
```
. build/envsetup.sh
```

Breakfast your device
```
breakfast <device codename>
```

Start the build
```
brunch <device codename>
```
