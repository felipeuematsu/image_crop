# Image crop for insta_assets_picker package

[![image_crop](https://img.shields.io/pub/v/image_crop?label=image_crop)](https://pub.dev/packages/image_crop)
[![insta_assets_picker](https://img.shields.io/pub/v/insta_assets_picker?label=insta_assets_picker)](https://pub.dev/packages/insta_assets_picker)

> **Warning**
> This repository is a fork from [image_crop](https://github.com/lykhonis/image_crop) and was modified to work with [insta_assets_picker](https://pub.dev/packages/insta_assets_picker) package.
> This means that this repository will only be updated for the means of this package.
> I don't recommend using it in your project as it probably won't be updated except for the insta_assets_picker requirement.

## Changes

Contains all the changes needed in order to work with the `insta_assets_picker` library :

- [#75](https://github.com/lykhonis/image_crop/pull/75): fix sample image on android
- [#77](https://github.com/lykhonis/image_crop/pull/77): disable initial magnification
- [#95](https://github.com/lykhonis/image_crop/pull/95): new `disableResize` parameter
- [#96](https://github.com/lykhonis/image_crop/pull/96): new `backgroundColor` parameter
- [#97](https://github.com/lykhonis/image_crop/pull/97): new `placeholderWidget` & `onLoading` parameters
- [#98](https://github.com/lykhonis/image_crop/pull/98): new `initialParam` parameter to initialize view programmatically
- [#104](https://github.com/lykhonis/image_crop/pull/104): add to support to Flutter 3.10.x
- [f34bfef](https://github.com/LeGoffMael/image_crop/commit/f34bfef5eaf7aef298c475fd1a1874adaa6bcad3): fix issue on aspect ratio change, no PR made because it might not be the best fix
- [8fb0bc0](https://github.com/LeGoffMael/image_crop/commit/8fb0bc04696f95055be5f3dc32cbb8714b278a9c): fix issue with GIF, no PR for this yet since it is specific to GIF extended image provider
- [c60f3a1](https://github.com/LeGoffMael/image_crop/commit/c60f3a1c6944725cb7cd07c901a44fd7f3b43653): fix compatibility with AGP 8.0
- [#3](https://github.com/LeGoffMael/image_crop/pull/3): replace `image` with `child` & `size` parameters. Allow any widget to be shown in the crop view.

## Note

Thanks to [lykhonis](https://github.com/lykhonis) who developed [image_crop](https://pub.dev/packages/image_crop).
If the original package happen to be updated, this could be deleted.
