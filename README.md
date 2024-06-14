# Ubuntu 24.04 Ansible Test Image

[![Build, test and push docker image](https://github.com/fernandobohrer/docker-ansible-ubuntu-2404/actions/workflows/build-test-and-push-docker-image.yml/badge.svg?branch=main&event=push)](https://github.com/fernandobohrer/docker-ansible-ubuntu-2404/actions/workflows/build-test-and-push-docker-image.yml) [![Docker Pulls](https://badgen.net/docker/pulls/fernandobohrer/docker-ansible-ubuntu-2404?icon=docker&label=pulls)](https://hub.docker.com/r/fernandobohrer/docker-ansible-ubuntu-2404/) [![Docker Image Size](https://badgen.net/docker/size/fernandobohrer/docker-ansible-ubuntu-2404?icon=docker&label=image%20size)](https://hub.docker.com/r/fernandobohrer/docker-ansible-ubuntu-2404/)

This repository contains a `Dockerfile` that is used to create a **Ubuntu 24.04** based docker container image with `ansible` and `systemd` preinstalled.

## 🚀 Motivation

The container image that is created from this repository can be used for Ansible role testing.

The `systemd` package is installed so that this container image can be used to test Ansible roles that deploy services.

## 📦 Build process

This container image is built and uploaded automatically to Docker Hub once a week and any time a commit is made or merged to the `main` branch.

## 🏷️ Tags

- `latest`: Latest stable version of `ansible`.

## ⚠️ Warning

Use this repository and the docker image that it creates at your own risk!
