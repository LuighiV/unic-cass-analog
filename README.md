Project template for analog flow
================================


This is based on the project template developed for Chipathon 2025 by Jianxun
Zhu. Here the files are adapted to the technology used in UNIC CASS 2025 which
is IHP.


To start working with it please run:

```
make start
```
or 

```
make start-vnc
```

place an .env file in the root repository to setup the options. Could use the
following as example:

```
DOCKER_USER=luighiv
ENABLE_GUI=1
WEBSERVER_PORT=80
VNC_PORT=5901
JUPYTER_PORT=8888
DOCKER_TAG=1.0.7_vnc
```

The shared directory is the subfolder `designs` so all the development is self
contained in the repository.

