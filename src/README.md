This is the smallest Blink example I could find for the Pi.

It comes from https://github.com/Pieter-Jan/PJ_RPI and is explained here http://www.pieter-jan.com/node/15

To compile the code for the Pi you have either to be on a Pi with build tools installed OR to use a cross-compiler.

To install build tools on a Pi:
---
apt-get update && apt-get install -y build-essential 

To cross-compile for the Pi:
---
The easiest when it come to cross compiling is to use this Docker image:
https://registry.hub.docker.com/u/sdt4docker/raspberry-pi-cross-compiler/

