# node-docker
Contains a docker file for an image based on `node-10` with docker installed, and script to build, tag and push
the image to the vimc docker hub.

## building
Run `./build-image.sh` to build and push to docker hub. This script is also run on BuildKite.

## usage
This image is used by [Montagu-Webapps](https://github.com/vimc/montagu-webapps) 
and [Montagu-Proxy](https://github.com/vimc/montagu-proxy)
