# Experiments with Hadoop cluster setups in Docker

This repository provides docker configurations for quick Hadoop cluster
setup.

## Basic Cluster
Provides a 1 `Namenode` and 2 `Datanode` setup.

How to use:
```shell
$ git clone https://github.com/codito/hadoop-expt.git
$ cd hadoop-expt
$ docker-compose -f hadoop-basic.yml up
```

Refer this blog post for more details: http://codito.in/hadoop-cluster-in-docker.

## Credits
Many thanks to [uhopper](https://bitbucket.org/uhopper/hadoop-docker) for
providing excellent base hadoop images.
