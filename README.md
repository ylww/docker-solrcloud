# solrcloud-docker
solrcloud tutorial using docker

## prerequirments
- install docker-compose

## init solrcloud

```
docker-compose up -d
```

## Creating Collection

```
docker exec -i -t solr1 /opt/solr/bin/solr create_collection -c collection1 -shards 2 -p 8983
```
