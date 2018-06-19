# Ansible Prometheus Role
[![Build Status](https://travis-ci.org/ContentWise/ansible-prometheus.svg?branch=master)](https://travis-ci.org/ContentWise/ansible-prometheus)

An Ansible Role that installs [Prometheus](https://prometheus.io/) on Linux.

## Role Variables

Available variables with their default values are defined in [defaults/main.yml](defaults/main.yml).

## Supported Platform

Checkout [Test Kitchen configuration](.kitchen.yml) to see what platforms are supported and tested.

## Test

Install required dependencies:

	bundle install

Run tests:

	kitchen test

## Example Playbook

Checkout [integration tests](test/integration) directory for example playbooks.

## License

Fork maintainer: Luca Florio <luca.florio@contentwise.tv>

Licensed under The MIT License (MIT). See the [LICENSE file](LICENSE) for details.
