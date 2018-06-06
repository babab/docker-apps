# wdocker vars:

#wd# docker = docker
#wd# name = bee
#wd# ports = -p 127.0.0.1:6667:6667

#wd# build = {docker} build -t {name} .
#wd# run = {docker} run -d {ports} --name {name} {name}

# wdocker commands:

#wd# start: {docker} start {name}
#wd# stop: {docker} stop {name}
#wd# shell: {docker} exec -it {name} bash
#wd# init: {build} && {run}

FROM debian:latest
MAINTAINER Jane Doe <user@example.org>
EXPOSE 6667
RUN apt-get update
RUN DEBIAN_FRONTEND=noninteractive apt-get install -y bitlbee
CMD /usr/sbin/bitlbee -D -n
