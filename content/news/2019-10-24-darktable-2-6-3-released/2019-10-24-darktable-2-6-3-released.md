author: Pascal Obry
date: 2019-10-24 18:20:00+00:00
layout: post
title: darktable 2.6.3 released
lede: fecamp.jpg
lede_author: <a href="http://photos.obry.net">Pascal Obry</a>
tags: announcement, darktable release

we’re proud to announce the third bugfix release for the 2.6 series of darktable, 2.6.3!

the github release is here: [https://github.com/darktable-org/darktable/releases/tag/release-2.6.3](https://github.com/darktable-org/darktable/releases/tag/release-2.6.3).

as always, please don't use the autogenerated tarball provided by github, but only our tar.xz. the checksums are:

```
$ sha256sum darktable-2.6.3.tar.xz
a518999c8458472edfc04577026ce5047d74553052af0f52d10ba8ce601b78f0  darktable-2.6.3.tar.xz
$ sha256sum darktable-2.6.3.1.dmg
cb79d40f7fb03ff9b4701c5f28d5f4d91b102756f48d970354d7102740e36f6d  darktable-2.6.3.1.dmg
$ sha256sum darktable-2.6.3-win64.exe
716bde75c7b1ba6d57344747773a7dde3a88b707bcceb8090062b02eed863bae  darktable-2.6.3-win64.exe
```

when updating from the currently stable 2.6.x series, please bear in mind that your edits will be preserved during this process, but it will not be possible to downgrade from 2.6 to 2.4.x any more.

#### Important note: to make sure that darktable can keep on supporting the raw file format for your camera, *please* read [this post](https://discuss.pixls.us/t/raw-samples-wanted/5420?u=lebedevri) on how/what raw samples you can contribute to ensure that we have the *full* raw sample set for your camera under CC0 license!

and the changelog as compared to 2.6.2 can be found below.

## New Features

- April 1st game is now disabled by default
- Add preference to disable/enable April 1st game
- Print module default margin set 17mm
- Add support for disabling base-curve by default
- Add support for disabling sharpen by default

## Bugfixes

- Source with OpenMP can be compiled with GCC-9 and clang
- Update skin tone preset on color-zones module
- Fix compiling with exiv2 0.27.2.1
- Fix file access permissions on macOS Catalina 10.15
- Fix shift+scroll only scrolling in one direction on macOS
- Fix picasa, piwigo and facebook SSL support
- Fix CSS issue on MacOS

## Changed Dependencies

None.

## Camera support, compared to 2.6.2

### Base Support

- Epson R-D1s
- Epson R-D1x
- Fujifilm FinePix F770EXR
- Fujifilm X-T30 (compressed)
- Fujifilm XF10
- Kodak EasyShare Z981
- Kodak EasyShare Z990
- Leica C (Typ 112) (4:3)
- Leica CL (dng)
- Leica Q (Typ 116) (dng)
- Leica Q2 (dng)
- Leica SL (Typ 601) (dng)
- Leica V-LUX (Typ 114) (3:2, 4:3, 16:9, 1:1)
- Olympus E-M1X
- Olympus TG-6
- Panasonic DC-G90 (4:3)
- Panasonic DC-G91 (4:3)
- Panasonic DC-G95 (4:3)
- Panasonic DC-G99 (4:3)
- Panasonic DC-ZS200 (3:2)
- Panasonic DMC-TX1 (3:2)
- Sony DSC-RX0M2
- Sony ILCE-6400
- Sony ILCE-7RM4

### White Balance Presets

- Panasonic DC-LX100M2

### Noise Profiles

- Panasonic DC-LX100M2