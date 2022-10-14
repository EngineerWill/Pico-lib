# Pico-lib
## 中文简介
为一些网络不好的地址提供Pico有关库
### 如何使用
* 下载有关编译库
```
 sudo apt update
 sudo apt install cmake gcc-arm-none-eabi libnewlib-arm-none-eabi build-essential -y
 sudo apt install automake autoconf build-essential texinfo libtool libftdi-dev libusb-1.0-0-dev -y
```
* 下载压缩包并解压
```
cd ~
sudo apt-get install p7zip-full -y
wget https://github.com/EngineerWill/Pico-lib/releases/download/v1.0/Pico-lib.7z
7z x ./Pico-lib.7z
```
### 安装openocd
```
cd ~/pico/openocd/
./bootstrap
./configure --enable-ftdi --enable-sysfsgpio --enable-bcm2835gpio
make -j4
sudo make install
```
## English
Provide pico lib for areas with poor network
### How to use
* Download the relevant compilation library
```
 sudo apt update
 sudo apt install cmake gcc-arm-none-eabi libnewlib-arm-none-eabi build-essential -y
 sudo apt install automake autoconf build-essential texinfo libtool libftdi-dev libusb-1.0-0-dev -y
```
* Download the package and unzip it
```
cd ~
sudo apt-get update
sudo apt-get install p7zip-full -y
wget https://github.com/EngineerWill/Pico-lib/releases/download/v1.0/Pico-lib.7z
7z x ./Pico-lib.7z
```
### install openocd
```
cd ~/pico/openocd/
./bootstrap
./configure --enable-ftdi --enable-sysfsgpio --enable-bcm2835gpio
make -j4
sudo make install
```
