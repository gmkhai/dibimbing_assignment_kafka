# Dibimbing, Data Engineering Bootcamp

1. Clone This Repo.
2. Run `make docker-build` for x86 user, or `make docker-build-arm` for arm chip user.

---
```
## docker-build                 - Build Docker Images (amd64) including its inter-container network.
## docker-build-arm             - Build Docker Images (arm64) including its inter-container network.
## postgres                     - Run a Postgres container
## spark                        - Run a Spark cluster, rebuild the postgres container, then create the destination tables
## jupyter                      - Spinup jupyter notebook for testing and validation purposes.
## airflow                      - Spinup airflow scheduler and webserver.
## kafka                        - Spinup kafka cluster (Kafka+Zookeeper).
## datahub                      - Spinup datahub instances.
## metabase                     - Spinup metabase instance.
## clean                        - Cleanup all running containers related to the challenge.
```

---
# Documentation Assignment

Please follow this command if you pull this repository

1. runing `make docker-build`
2. runing `make jupyter`
2. runing `make kafka`
3. runing `make kafka-create-topic` because I am create new topic for this assignment

After that you can runing jupyter file:
1. `notebooks/Dibimbing-kafka-assign-produce.ipynb` for produce generate message using protopuf formating
2. `notebooks/Dibimbing-kafka-assign-consume.ipynb` for 
read message 

Protobuf formating save in directory `notebooks/proto`

