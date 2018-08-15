# docker-spark

The easiest way to start playing with Apache Spark

## Prerequisites

- docker
- docker-compose

## How to build the spark docker image

```
$ docker build --rm -t vitaled/docker-spark -f spark/Dockerfile . 
```

## How to start a standalone cluster using docker-compose

```
$ docker-compose -f docker-compose-standalone.yml up 
```

## How to start using the spark shell 

```
$ docker exec -ti docker-spark_master_1 spark-shell
```

