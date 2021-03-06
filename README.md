three.dart
========

#### Dart 3D Engine ####

This project aims to port the [three.js](https://github.com/mrdoob/three.js) JavaScript 3D engine to [Dart](http://www.dartlang.org/).

Starting at three.js revision 47.0, the aim is to recreate all of the existing three.js [examples](http://mrdoob.github.com/three.js/), until parity is reached with this version. Beyond this point, further revisions to three.js will be closely followed and matched in three.dart.

### Change Log ###

2012 02 12 - **r1.1**

Project restructuring:
  - "ThreeD" renamed to "src"
  - "examples" folder introduced

2012 02 11 - **r1**

* Pre-alpha release (I can see a cube!! :D - Tested in Google Chrome Browser on Windows 7)
* This code is not currently ready to be used in a project
* Canvas_Geometry_Cube example partially implemented
* Only code essential to Canvas_Geometry_Cube has been ported (e.g. CanvasRenderer, but not WebGLRenderer)