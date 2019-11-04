# Notes

## Docker

### Installing Docker

*	[Ubuntu](https://docs.docker.com/engine/installation/linux/docker-ce/ubuntu/)
*	[Fedora](https://docs.docker.com/engine/installation/linux/docker-ce/fedora/)
*	[Windows 10 Pro/Enterprise/Education](https://docs.docker.com/docker-for-windows/install/)
* [Windows 7, 8, 10 Home](https://docs.docker.com/toolbox/toolbox_install_windows/)
*	[Getting started](https://docs.docker.com/get-started/)

### Starting python container

The following command starts a container with the Notebook server listening for HTTP connections on port 8888 with a randomly generated authentication token configured.

```
docker run -it --rm -p 127.0.0.1:8888:8888 simwelten/jupyter
```

Take note of the authentication token included in the notebook startup log messages. Include it in the URL you visit to access the Notebook server or enter it in the Notebook login form.

### Getting the newest image

To update your local image to the latest version run:

```
docker pull simwelten/jupyter:latest
```


## Tutorials

*	[Python 3 tutuorial](https://gitlab.erc.monash.edu.au/andrease/Python4Maths) is already in the container

