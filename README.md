# Server Pi | Docker Files
I am using a [Raspberry Pi 4](https://www.raspberrypi.com/products/raspberry-pi-4-model-b/) running [Debian](https://raspi.debian.net/) as home server. On it I use Docker to quickly install and test various tools and applications without the need to make server-wide adjustmenst, which might affect other installed services.

Because only one container my bind to a single port I used [this helpful blog post](https://blog.florianlopes.io/host-multiple-websites-on-single-host-docker/) to setup a reverse-proxy with nginx.