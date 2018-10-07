# GCodeViz #
![macOS building status](https://travis-ci.org/Serge45/GCodeViz.svg?branch=master)
[![Build status](https://ci.appveyor.com/api/projects/status/vyi83bx3gjkox338?svg=true)](https://ci.appveyor.com/project/Serge45/gcodeviz)

Open source G-Code visualization tool

![demo](images/gcodeviz-octocat.gif)

## Implemented Functions ##
 - Load G-Codes
 - Visualize supported G-Codes
 - Rotate G-Code view
 - Pan G-Code view
 - Convert to Servotronix softMC compatible motion program
 - Adjust drawing progress after G-Code rendered

## Supported G-Code ##
 - G00
 - G01
 - G02
 - G03
 - G17
 - G18
 - G19
 - G90
 - G91

## Building Instructions ##
 Requirements:
 - Qt 5.4+
 - Compiler that supports C++11
### macOS ##
 - Install [homebrew](https://brew.sh)
 - `brew install qt5`
 - `brew cask install qt-creator`
 - Open and build `GCodeViz.pro` via Qt-Creator

### License ###
 - MIT
