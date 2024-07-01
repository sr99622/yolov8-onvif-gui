yolov8-onvif-gui
================

A drop in module for [Onvif GUI](https://github.com/sr99622/libonvif) for performing object detection on camera video streams. To add the module to an
exisiting installation, copy the yolov8.py file to the modules/video subdirectory of the site-packages location of the python environment into which
Onvif GUI was installed. For example, if Onvif GUI was installed into a virtual environment named myenv as described in the installation instructions,
the target directory would look something like shown below.

```/home/stephen/myenv/lib/python3.12/site-packages/modules/video```

After copying the file, it is necessary to install the dependencies using the command ```pip install ultralytics```

This file was created using software developed by Ultralytics and is used under the [AGPL-3.0 license](https://github.com/ultralytics/ultralytics?tab=AGPL-3.0-1-ov-file#AGPL-3.0-1-ov-file)
