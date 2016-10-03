# arm-toolchain-mac
A cross-compiler toolchain for macOS (10.12) host and arm-linux-gnueabihf target optimized for cortex-a7 (Raspberry Pi 2).

#### Installation
Checkout to /usr/local/arm-unknown-linux-gnueabihf and add /usr/local/arm-unknown-linux-gnueabihf/bin to PATH.

#### Components and Versions
* gcc 6.2.0, glibc 2.24, binutils 2.26, gdb 7.11.1 (built with crosstool-ng)
* boost 1.62.0
* OpenCV 3.1.0
* Raspicam (https://github.com/cedricve/raspicam)
* Qt 5
* System libraries (X11, OpenGL) are taken from FedBerry 24
