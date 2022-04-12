# Docker
Apuntes sobre Docker

**Comandos**
> Obtener versión
>> docker version

> Ver lista comandos ayuda
>> docker --help

> Add user to docker group
>> sudo usermod -aG docker $USER

> Enable changes in docker group
>> newgrp docker 

> Resolver conflicto de mount
>> sudo mkdir /sys/fs/cgroup/systemd
>> sudo mount -t cgroup -o none,name=systemd cgroup /sys/fs/cgroup/systemd

> Ejecutar hello world container
>> docker run hello-world

> Ver contenedores ejecutandose
>> docker ps