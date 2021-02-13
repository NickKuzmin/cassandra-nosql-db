# Cassandra

> docker pull cassandra

Check version:
> docker run -it --rm --name cassandra-container-name cassandra -v

> docker network create --driver nat cassandra-network-name

> docker run --name cassandra-container-name --network cassandra-network-name -d cassandra

> docker run -it --network cassandra-network-name --rm cassandra cqlsh cassandra-container-name

