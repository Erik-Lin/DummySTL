DummySTL
## Introduction

This is a `tinySTL` based on `C++11`, which is my first project for practice. Now I have released version `2.0.0`. I have achieved the vast majority of the containers and functions of `STL`, and there may be some deficiencies and bugs. 

From the version `2.x.x`, the project will enter the stage of long-term maintenance, i.e., I probably will not add new content but only fix bugs found. If you find any bugs, please point out that in `Issues`, or make a `Pull requests`to improve it, thanks!

## Supported

* os
  * linux
  * windows
  * osx
* complier
  * g++ 5.4 or later
  * clang++ 3.5 or later

## Run test

If you want to run the test, please read `test/README.md` first.

* gcc/clang on linux/osx

1. git clone
```bash
$ git clone https://github.com/Erik-Lin/DummySTL.git dummystl
$ cd dummystl
```
2. build and run
```bash
$ mkdir build && cd build
$ cmake ..
$ make
$ cd ../bin && ./stltest
```