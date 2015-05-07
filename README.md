# piblink

Simple example of how to build, package and deploy a Blink example for the Raspberry pi using Docker.

The resulting image is available in the Docker hub at: https://registry.hub.docker.com/u/ffleu/piblink/

To deploy it on your Pi you need to run an image which support docker. We are using the one from hypriot: http://blog.hypriot.com/post/hypriotos-back-again-with-docker-on-arm/

Just burn the image on the SD card and you should ne able to pull and run the Blink application in a container.


```
$ docker pull ffleu/piblink:v1
Pulling repository ffleu/piblink
0bef68b9f428: Download complete 
cde0b76acde0: Download complete 
dc5ef85a555a: Download complete 
b740f04f5d5d: Download complete 
77a09545d99d: Download complete 
9648d6e9e7fa: Download complete 
Status: Downloaded newer image for ffleu/piblink:v1
HypriotOS: pi@black-pearl in ~
$ docker run ffleu/piblink:v1
Failed to open /dev/mem, try checking permissions.
Failed to map the physical GPIO registers into the virtual memory space.
HypriotOS: pi@black-pearl in ~
$ docker run --privileged ffleu/piblink:v1
```
