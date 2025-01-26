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
and then launch chromium:
```
~/chrome
```
