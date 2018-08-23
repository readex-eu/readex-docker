## readex-docker
This repository provides a docker file that enables you to create a READEX docker image.

### Steps to create docker image:
1. Install [Docker](https://www.docker.com/).
2. Download [READEX dockefile](https://github.com/readex-eu/readex-docker/blob/master/Dockerfile.readex_gcc7.3.0).
3. Build the READEX docker image from the dockerfile in the current directory

   `docker build -t="docker/readex" -f Dockerfile.readex_gcc7.3.0 .`

### Steps to run docker image:

   `docker run -it --rm docker/readex_gcc7.3.0_v01`
