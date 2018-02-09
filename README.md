# Notes

## Docker

### Installing Docker

*	[Ubuntu](https://docs.docker.com/engine/installation/linux/docker-ce/ubuntu/)
*	[Fedora](https://docs.docker.com/engine/installation/linux/docker-ce/fedora/)
*	[Windows](https://docs.docker.com/docker-for-windows/install/)
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

## Data
	
*	[S-Bahn Stuttgart RIS-Archiv-Daten](http://data.deutschebahn.com/dataset/data-s-bahn-stuttgart-ris-archiv-daten) - in the container as well

