# x264 iOS build script

**My blog: [http://www.jianshu.com/u/1cac5c2fc495](http://www.jianshu.com/u/1cac5c2fc495)**

This is a shell script to build x264 for iOS apps.

Tested with:

* x264-snapshot-20170904-2245
* Xcode 8.3.2

## Requirements

* https://github.com/libav/gas-preprocessor

## Usage

* To build everything:

        ./build-x264.sh

* To build for arm64:

        ./build-x264.sh arm64

* To build fat library for armv7 and x86_64 (64-bit simulator):

        ./build-x264.sh armv7 x86_64

* To build fat library from separately built thin libraries:

        ./build-x264.sh lipo

