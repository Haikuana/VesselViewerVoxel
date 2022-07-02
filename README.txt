####################################################
Prject: 3D Printing Voronoi-cells Structure
Author: Haikuan Zhu
Date:   0208-2020
####################################################

## Getting Started

The source directory tree holds source code to the OOFEM package.  

  VorPrinting
  |
  |-- cmake/tools - contains some essential documents of GEOGRAM! 
  |
  |-- src - source files of all modules
  |   |
  |   |
  |   bin - sources of executable libs 
  |   |		|
  |   |		|
  |   |		|-- GeangeGUI - gui of range-lib which can be used for computing stress
  |   |		|
  |   |		|-- vorpalite - geogram lib
  |   |		|
  |   |		|-- vorpaview - geogram gui
  |   |		|
  |   |		|-- VorPrint  - combined lib for generating voronoi-cell structure
  |   |
  |   lib - sources of static libs (indirectly used)
  |   |		|
  |   |		|-- third_party - libs for gui: glfw
  |   |		|
  |   |		|-- range       - contains the sources and implementation of range lib 
  |   |     |        
  |   |     |-- geogram_gfx  
  |   |     |-- geogram    



### Pre-requisites

This project requires the CMake cross-platform build system and C++ compiler with STL support (Standard Template Library).

third_party: 	Geogram - (Imgui-glfw glad ... other(unused))
				Range	- (ffmpeg QT5)
				CGAL    -- need installation!!!
				Eigen
				QT      -- need installation!!!




## Copyright 
This program is free software; you can redistribute it and/or modify it under the terms of the GNU General Public License
 as published by the Free Software Foundation; either version 2 of the License, or (at your option) any later version.

Copyright (C) Haikuan Zhu