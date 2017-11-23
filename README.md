# resin-multi-container

**THIS IS WORK IN PROGRESS**

Multiple containers example based on [this](https://github.com/justin8/resin-multi-container) project. 

Updated to work with ResinOS v2+ running dnsmasq and Docker bridge on `10.114.101.1/24`.

Tested on Intel NUC and QEMU devices (x86_64).

The application starts a docker-in-docker instance and runs docker-compose.
docker-compose then builds and runs the containers.

You can edit docker-compose.yml to add the containers you need.

For docker in docker, check [jpetazzo/dind](https://github.com/jpetazzo/dind).
