# This is an auto generated Dockerfile for gazebo:gzclient6
# generated from templates/docker_images/create_gzclient_image.Dockerfile.em
# generated on 2016-04-27 20:25:03 +0000
FROM gazebo:gzserver6
MAINTAINER Steven Peters scpeters+buildfarm@osrfoundation.org

# install packages
RUN apt-get update && apt-get install -q -y \
    binutils \
    mesa-utils \
    module-init-tools \
    x-window-system\
    && rm -rf /var/lib/apt/lists/*

# install gazebo packages
RUN apt-get update && apt-get install -q -y \
    gazebo6=6.6.0* \
    && rm -rf /var/lib/apt/lists/*
