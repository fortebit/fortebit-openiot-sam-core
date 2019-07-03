# Fortebit OpenTracker - Arduino Core (SAM Architecture) [![GitHub release](https://img.shields.io/github/release/fortebit/fortebit-openiot-sam-core.svg)](https://github.com/fortebit/fortebit-openiot-sam-core/releases/latest)

This repository contains the source code and configuration files of the Arduino Core for Atmel's SAM3XA Series of microcontrollers and board support files for the [OpenTracker v2](https://fortebit.tech/open-iot-platform/) board (mostly compatible with [Arduino Due](https://www.arduino.cc/en/Main/ArduinoBoardDue)).

## Installation on Arduino IDE

This core is included in the [Fortebit Open IoT Board Manager](https://github.com/fortebit/fortebit-openiot-arduino-boards) package. Please refer to that page for installation instructions.

## Development with Git

This repository references other projects (mainly libraries) as Git sub-modules. To setup your local copy of the repository make sure to run (from the repository root directory):

```
git submodule init
git submodule update --recursive
```
