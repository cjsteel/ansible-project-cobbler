# README.md

## Description

## Project configuration

From the project directory run
```shell
ansible-galaxy install amtega.ansible
```

## Project Testing with Molecule

This is an experiment, if you use molecule the normal way this may be somewhat confusing.

```shell
cd roles/csteel.common
molecule --debug converge -s lxd
```

## Requirements

* lxd
* molecule
