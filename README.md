# piblink

Simple example of how to build, package and deploy a Blink example for the Raspberry pi using Docker.

The resulting image is available in the Docker hub at: https://registry.hub.docker.com/u/ffleu/piblink/

To deploy it on your Pi you need to run an image which support docker. We are using the one from hypriot: http://blog.hypriot.com/post/hypriotos-back-again-with-docker-on-arm/

Just burn the image on the SD card and you should ne able to pull and run the Blink application in a container.
