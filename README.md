=====================================
OpenMVG (open Multiple View Geometry)
=====================================

An openSource camera sensor size database.

------------
Introduction
------------

This repository contains a list of camera model and their corresponding camera sensor size.

Linking image entry to image EXIF data allow to compute approximate focal length (in pixels)

focal_pix = (max( w, h ) * focal_mm) / ccdw_mm

  - focal_pix: the focal length in pixels,
  - focal_mm: the EXIF focal length (mm),
  - w,h  the image of width and height (pixels),
  - ccdw_mm: the known sensor width size (mm).

------------
Description
------------

CSV version:

    CameraMaker;CameraModel;CameraSensorWidth(mm)

Contributions to the database are welcome (please use the pull request mechanism)
 
-------
License
-------

See [LICENSE MPL2](https://github.com/openMVG/cameraSensorSizeDatabase/raw/master/license.openMVG) text file
