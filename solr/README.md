# Solr Docker

Right now it works to copy over your Solr configuration to /opt/solr/server/solr directory within the container.  It might be easier to look at
working with volume mounts, since the volumes seems to have issue with permissions.  I beileve this is true since the active user is Solr and there
is no Solr user on the native system.

## Configuration
volumes:
    - ~/data/docker/solr:/opt/solr/server/solr
    
## Solr Cloud Docker
Need to create the collection tweets:
    docker exec -i -t solr1 /opt/solr/bin/solr create_collection -c tweets -shards 2 -p 8983
