# Elasticsearch cluster with cerebro on docker
This is elasticsearch v5.3.3 cluster on docker with cerebro, 1 ingest, 3 masters and 6 datanodes
![Host](https://raw.githubusercontent.com/m1g0r/elasticsearch-cluster-docker/master/img/cerebro-es533.png)
## Getting Started
In order to run in Linux:
```
sysctl -w vm.max_map_count=262144
```
Up docker-compose:

```
docker-compose up -d
```