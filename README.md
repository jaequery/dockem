# Dockem

Dockem allows you to run an optimized and streamlined web development environment for Docker on Mac OSX

### Requirements

- You need to be running a specific beta version of Docker for Mac (Edge) v2.3.4.0

### Install

1. Download and install Docker for Mac Edge 2.3.4 (https://desktop.docker.com/mac/edge/46980/Docker.dmg)

2. Clone the repo 

```
git clone git@github.com:jaequery/dockem.git
cd dockem
```

3. Copy the DNS resolver file to your /etc/resolver so that it forwards all domains ending in .docker to point to your Docker containers

```
sudo cp data/etc/resolver/docker /etc/resolver/
```

4. Start it up using Docker Compose

```
docker-compose up -d
```
