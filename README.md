# Manjaro ARM GNOME Profile

[![prerelease_build_gnome](https://github.com/manjaro-arm-community/gnome-images/actions/workflows/prerelease_build_gnome.yaml/badge.svg)](https://github.com/manjaro-arm-community/gnome-images/actions/workflows/prerelease_build_gnome.yaml)
[![release_build_gnome](https://github.com/manjaro-arm-community/gnome-images/actions/workflows/release_build_gnome.yaml/badge.svg)](https://github.com/manjaro-arm-community/gnome-images/actions/workflows/release_build_gnome.yaml)

![current screenshot](https://user-images.githubusercontent.com/6803419/109429579-a6ace400-79fc-11eb-92ef-3269f098263f.png)

## description

Release Branch for Manjaro ARM GNOME profile images

## where can I download an image?

Images are build and uploaded in a relatively regular interval to [github releases](https://github.com/manjaro-arm-community/gnome-images/releases)

## sources

- [image profile](https://github.com/manjaro-arm-community/arm-profiles)

## building

1. check out the arm-profiles
2. `sudo buildarmimg -d $DEVICE -e $EDITION -b $BRANCH -v $VERSION` 
