areaDetector
==========

This is the project for [EPICS](http://www.aps.anl.gov/epics/) areaDetector software.
 
The areaDetector code is contained in repositories in this project.
Five of these are "core" repositories:

1. [areaDetector](https://github.com/areaDetector/areaDetector). 
  This is the top-level repository, and all other repositories are submodules of this repository.
  It contains mostly documentation, configuration files, and a top-level Makefile to build the entire areaDetector package.
2. [ADSupport](https://github.com/areaDetector/ADSupport). 
  This contains the source code for support libraries (TIFF, JPEG, HDF5, XML2, etc.).
  This is required for Windows and vxWorks, and can optionally be used on Linux and Darwin.
3. [ADCore](https://github.com/areaDetector/ADCore).
  This contains the base classes, plugins, and documentation.
4. [ADSimDetector](https://github.com/areaDetector/ADSimDetector).
  This contains an example 2-D simulation detector driver and IOC.
5. [ADViewers](https://github.com/areaDetector/ADViewers).
  This contains viewers for displaying areaDetector images in ImageJ, Python, and IDL.
  
The other submodules (ADProsilica, ADPilatus, etc.) contain drivers and EPICS IOC applications
for specific detectors, or non-standard plugins (ADPluginBar, ADPluginEdge, etc.)

Additional information:
* [Documentation home](https://areadetector.github.io/areaDetector/index.html).
* [Installation Guide](https://areadetector.github.io/areaDetector/install_guide.html)
* [User Guide](https://areadetector.github.io/areaDetector/user_guide.html).
* [Release notes and links to source and binary releases](https://github.com/areaDetector/areaDetector/blob/master/RELEASE.md).
