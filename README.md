# arm-toolchain-mac
Toolchain for OS X host and arm-linux-gnueabihf target optimized for cortex-a7 (Raspberry Pi 2).

Checkout to /usr/local/arm-cortex_a7-linux-gnueabihf and add /usr/local/arm-cortex_a7-linux-gnueabihf/bin to PATH

#### Components and Versions
* gcc 5.4.0, glibc 2.24, binutils 2.26, gdb 7.11.1 (built with crosstool-ng)
* boost 1.63.0 (with context & fiber from HEAD)
* OpenCV 3.1.0
* Raspicam (https://github.com/cedricve/raspicam)
* Qt 5
* System libraries (X11, OpenGL) are taken from FedBerry 24
