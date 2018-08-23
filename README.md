## readex-docker
This repository provides a docker file that enables you to create a docker image to use the READEX tool suite (www.readex.eu).

### Steps to create docker image:
1. Install [Docker](https://www.docker.com/).
2. Download [READEX dockefile](https://github.com/readex-eu/readex-docker/blob/master/Dockerfile.readex_gcc7.3.0).
3. Build the READEX docker image from the dockerfile in the current directory

   `docker build -t="docker/readex_gcc7.3.0" -f Dockerfile.readex_gcc7.3.0 .`

### Steps to run docker image:

   `docker run -it --rm docker/readex_gcc7.3.0`

#### Note
All environment variables that are required to use the individual tools in the READEX tool suite are set in the docker image.

For questions, contact us at https://www.readex.eu/index.php/contact/, or the author (Venkatesh Kannan, venkatesh.kannan@ichec.ie).
