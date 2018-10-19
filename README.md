# Official Ansible image on Scaleway

[![Travis](https://img.shields.io/travis/scaleway/image-app-ansible.svg)](https://travis-ci.org/scaleway/image-app-ansible)
[![Scaleway ImageHub](https://img.shields.io/badge/ImageHub-view-ff69b4.svg)](https://hub.scaleway.com/ansible.html)
[![Run on Scaleway](https://img.shields.io/badge/Scaleway-run-69b4ff.svg)](https://cloud.scaleway.com/#/servers/new?image=coming-soon)

Scripts to build the official Ansible image on Scaleway

This image is built using [Image Tools](https://github.com/scaleway/image-tools) and depends on the official [Ubuntu](https://github.com/scaleway/image-ubuntu) image.

![](http://cdn2.hubspot.net/hub/330046/file-769078210-png/Official_Logos/ansible_logo_black_square_small.png?t=1434977424426)


---

**This image is meant to be used on a C1 server.**

We use the Docker's building system and convert it at the end to a disk image that will boot on real servers without Docker. Note that the image is still runnable as a Docker container for debug or for inheritance.

[More info](https://github.com/scaleway/image-tools)


---

## Install

Build and write the image to /dev/nbd1 (see [documentation](https://www.scaleway.com/docs/create_an_image_with_docker))

    $ make install

Full list of commands available at: [scaleway/image-tools](https://github.com/scaleway/image-tools/#commands)


---

A project by [![Scaleway](https://avatars1.githubusercontent.com/u/5185491?v=3&s=42)](https://www.scaleway.com/) [![GuardRails badge](https://badges.production.guardrails.io/moul/image-app-ansible.svg)](https://www.guardrails.io)
