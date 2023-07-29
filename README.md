# Docker

Creating docker file for python-image

FROM :This specifies the base image to use for the Docker image.

RUN: This run a command inside the docker container during the build process.

COPY: This copies files from the local file sysytem to the Docker image.

WORKDIR: This sets the working directory for subsequent commands in the Dockerfile.

CMD: This specifies the command to run when the Docker container starts.


Dockerfile : 
A text file with instructions to build image
Automation of Docker Image Creation

FROM
RUN
CMD

Step 1 : Create a file named Dockerfile

Step 2 : Add instructions in Dockerfile

Step 3 : Build dockerfile to create image : docker build -t imagename

Step 4 : Run image to create container : docker run imagename 

COMMANDS
: docker build 
: docker build -t ImageName:Tag directoryOfDocekrfile

: docker run image