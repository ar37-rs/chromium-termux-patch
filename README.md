# Patch enable WebGL 2.0 using angle for chromium termux 

## Install chromium:
```
pkg install tur-repo && pkg install chromium
```

# Install patch
```
cd && pkg install wget && wget https://github.com/ar37-rs/chromium-termux-patch/releases/download/latest/chrome && chmod +x ~/chrome
```
## Usage:
use command to start patching like so:
```
~/chrome patch
```
and start chromium:
```
~/chrome
```

# Using angle-android (built 2024.12.13):

## Install:
```
cd && wget https://github.com/ar37-rs/virgl-angle-termux/releases/download/2.1.24533/angle-android_2.1.24533_aarch64.deb
dpkg -i angle-android_2.1.24533_aarch64.deb
```



