FROM ubuntu:16.04
MAINTAINER Provable "info@provable.xyz"

RUN apt-get update && apt-get install bc
CMD echo $ARG0 + $ARG1 | /usr/bin/bc \
   && exit 0;
