# smokris's useless [Vuo](http://vuo.org) nodes
[![Build Status](https://travis-ci.org/smokris/vuo-nodes.svg?branch=master)](https://travis-ci.org/smokris/vuo-nodes)

These nodes are built for Vuo 1.2.x.  You may need to modify and rebuild them to use them with other Vuo versions.

## To install
   - Go to the [Releases page](https://github.com/smokris/vuo-nodes/releases) and download the latest binary release (not the source code).
   - Unzip the archive, and copy its contents into your `~/Library/Application Support/Vuo/Modules` folder.

## Nodes

Node                                        | Output
------------------------------------------- | ------------------------------------------------
`Get Message Values (List)`                 |
![](smokris/smokris.macam.receive.png)<br>Uses https://github.com/smokris/macam64 to stream video from old USB cameras, such at the Intel QX3 microscope. | <img src="smokris/smokris.macam.receive-output.png" width="320">
![](smokris/smokris.snapshot.png)           |
![](smokris/smokris.make.glitch.image.png)<br>Works on Mac OS 10.11 and earlier.<br>In macOS 10.12, Apple changed the OpenGL driver behavior such that this glitch technique is no longer available (see [#1](https://github.com/smokris/vuo-nodes/issues/1)). | <img src="smokris/smokris.make.glitch.image-output.png" width="320">
![](smokris/smokris.make.glitch.points.png) | <img src="smokris/smokris.make.glitch.points-output.png" width="320">
![](smokris/smokris.object.reinterpret.png) | <img src="smokris/smokris.object.reinterpret-output.png" width="320">
