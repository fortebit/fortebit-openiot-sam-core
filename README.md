# OpenTracker v2 - Arduino Core (SAM Architecture) [![GitHub release](https://img.shields.io/github/release/geolink/opentracker-sam-core.svg)](https://github.com/geolink/opentracker-sam-core/releases/latest)


This repository contains the source code and configuration files of the Arduino Core for Atmel's SAM3XA Series of microcontrollers and board support files for the [OpenTracker v2](https://geolink.io/opentracker.php) board (mostly compatible with [Arduino Due](https://www.arduino.cc/en/Main/ArduinoBoardDue)).

## Installation on Arduino IDE

This core is included in the [OpenTracker Board Manager](https://github.com/geolink/opentracker-arduino-board) package. Please refer to that page for installation instructions.

## Development with Git

This repository references other projects (mainly libraries) as Git sub-modules. To setup your local copy of the repository make sure to run (from the repository root directory):

```
git submodule init
git submodule update --recursive
```
