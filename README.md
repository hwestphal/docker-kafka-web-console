## Kafka Web Console Dockerfile


This repository contains **Dockerfile** of [Kafka Web Console](https://github.com/claudemamo/kafka-web-console) for [Docker](https://www.docker.com/)'s [automated build](https://registry.hub.docker.com/u/hwestphal/kafka-web-console/) published to the public [Docker Hub Registry](https://registry.hub.docker.com/).


### Base Docker Image

* [dockerfile/java:oracle-java7](http://dockerfile.github.io/#/java)


### Usage

    docker run -d -p 9000:9000 -v <persistent-db-and-logs-dir>:/data hwestphal/kafka-web-console

After few seconds, open `http://<host>:9000/` to see the starting page.
