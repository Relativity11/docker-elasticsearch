# docker-elasticsearch
Simple containerized elasticsearch with kibana for testing. 
Replicas are turned off.
index.translog.durability is off.


# Requirements
1. .env file for ELASTIC_PASSWORD, KIBANA_PASSWORD, CLUSTER_NAME
2. Assumes lite hardware (HDD Safe) for simple testing.
3. volumes have been created or adjusted:
     - /YOURVOLUME/docker/elastic/elasticsearch/data
     - /YOURVOLUME/docker/elastic/kibana/data
    

# Process
1. Prepare .env file
2. Run docker-compose up -d in directory path.