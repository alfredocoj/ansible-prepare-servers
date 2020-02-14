# ansible-prepare-servers

## Pre-requirements

```sh
$ sudo apt-key adv --keyserver keyserver.ubuntu.com --recv-keys 93C4A3FD7BB9C367
$ sudo apt update
$ sudo apt install ansible
```

## Commands:

```sh
$ ansible-playbook -i ansible-hosts ansible-vms.yaml

$ ansible-playbook -i ansible-hosts ansible-vms-docker.yaml
```

