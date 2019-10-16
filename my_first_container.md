My first container
=============

run the next command

```sh
$ docker run -it --rm --name prueba ubuntu 
```
let's take a look, open another terminal and execute:

```sh
$ docker ps 
```
show someting like that

```sh
CONTAINER ID        IMAGE               COMMAND             CREATED             STATUS              PORTS               NAMES
4fd5caac600b        ubuntu              "/bin/bash"         13 seconds ago      Up 11 seconds                           prueba
```
our first container is running..!!!
