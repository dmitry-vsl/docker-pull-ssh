Script for fast upload of docker images via SSH.

Script start docker registry locally, opens SSH tunnel to remote machine and
pulls images on remote machine from local registry. On complete is shuts down
registry.

Usage:

```
docker-push-ssh SSH_HOST IMAGE1 IMAGE2 ...
```
