---
author: houz
comments: true
date: 2016-07-05 09:36:30+00:00
layout: post
link: /2016/07/darktable-2-0-5-released/
slug: darktable-2-0-5-released
title: darktable 2.0.5 released
lede: landscape_wide.jpg
lede_author: <a href="https://houz.org/">houz</a>
wordpress_id: 4155
tags:
  - announcement
  - darktable release
---
we're proud to announce the fifth bugfix release for the 2.0 series of darktable, 2.0.5!

the github release is here: [https://github.com/darktable-org/darktable/releases/tag/release-2.0.5](https://github.com/darktable-org/darktable/releases/tag/release-2.0.5).

as always, please don't use the autogenerated tarball provided by github, but only our tar.xz. the checksum is:

    $ sha256sum darktable-2.0.5.tar.xz
    898b71b94e7ef540eb1c87c829daadc8d8d025b1705d4a9471b1b9ed91b90a02 darktable-2.0.5.tar.xz
    $ sha256sum darktable-2.0.5.dmg
    e0ae0e5e19771810a80d6851e022ad5e51fb7da75dcbb98d96ab5120b38955fd  darktable-2.0.5.dmg

and the changelog as compared to 2.0.4 can be found below.

## New Features

* Add geolocation to watermark variables

## Bugfixes

* Mac: bugfix + build fix
* Lua: fixed dt.collection not working
* Fix softproofing with some internal profiles
* Fix non-working libsecret pwstorage backend
* Fixed a few issues within (rudimentary) lightroom import
* Some fixes related to handling of duplicates and/or tags

## Base Support

* Canon EOS 80D (no mRAW/sRAW support!)

## White Balance Presets

* Canon EOS 80D

## Noise Profiles

* Canon EOS 80D

## Translations Updates

* Danish
* German
* Slovak