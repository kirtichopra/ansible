# ansible

This ansible code contain only on role right now, that is to initialize docker swarm mode and join other node as a worker.

##How to use ??

Edit the hosts file and add your master and worker server's IP's

```sh
ansible-playbook -i hosts -u <user-name> --ask-pass docker_swarm.yml --tags "dockerswarm"
```
