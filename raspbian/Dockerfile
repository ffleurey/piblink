# Start from the latest image provided by Resin
FROM resin/rpi-raspbian:latest

# Copy the binary program cross-compiled for the Pi
COPY ./Blink /app/Blink
WORKDIR /app

# Start blink app
CMD /app/Blink

