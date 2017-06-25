# Ansible

This ansible repo contain only one role right now, that is to initialize docker swarm mode and join other node as a worker.

This will setup your docker swarm cluster and install [portaier.io](https://portainer.io/) as a continer

### How to use ??

Edit the hosts file to update your master and worker servers IP's

```sh
ansible-playbook -i hosts -u <user-name> --ask-pass docker_swarm.yml --tags "dockerswarm"
```

New roles will be added every weekends.
