# README.md

## Description

Enable running of amtega.cobbler role from common role via molecule. 

## Resources

* https://galaxy.ansible.com/amtega/cobbler

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

amtega.cobbler role dependencies (installed when running ansible-galaxy command from projects directory).

| [amtega.check_platform](https://galaxy.ansible.com/amtega/check_platform) |
| ------------------------------------------------------------ |
| [amtega.epel](https://galaxy.ansible.com/amtega/epel)        |
| [amtega.packages](https://galaxy.ansible.com/amtega/packages) |
| [amtega.proxy_client](https://galaxy.ansible.com/amtega/proxy_client) |
| [amtega.tftpd](https://galaxy.ansible.com/amtega/tftpd)      |
| [amtega.xinetd_service](https://galaxy.ansible.com/amtega/xinetd_service) |