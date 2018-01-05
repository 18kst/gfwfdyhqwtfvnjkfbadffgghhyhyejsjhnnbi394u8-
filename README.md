# boot2flappy
Flappy Bird for UEFI written in x86 Assembly.

![Alt Text](resources/screenshot.png)

## Getting the source
Download the source code by running the following code in your command prompt:
```sh
$ git clone https://github.com/fabianishere/boot2flappy.git
```
or simply [grab](https://github.com/fabianishere/boot2flappy/archive/master.zip) 
a copy of the source code as a Zip file.

## Building
Create the build directory.
```sh
$ mkdir build
$ cd build
```
boot2flappy requires CMake and a C cross-compiler (mingw-w64-x86-64) in order to build.
On Ubuntu, please install the following packages:

- binutils-mingw-w64 
- gcc-mingw-w64-x86-64

Then, simply create the Makefiles:
```sh
$ cmake ..
```
and finally, build it using the building system you chose (e.g. Make):
```sh
$ make
```

## Playing
After building the project, just run the following code in your command prompt:
```sh
$ vm/start.sh
```
This will start a Qemu virtual machine in which you can play the game.

## Why
I had to post this on GitHub because It is amzing and you can not copy because it has a license also this app is on App Store & Play Store!

## License
The code is released under the Apache 2.0 License to view go above and click LICENSE.

All sprite files in the `resources` directory: all copyrights belong to their 
respective owners. The files are used for education purpose only.
