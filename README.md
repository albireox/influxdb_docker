# InfluxDB + Grafana Docker Compose

To run, make sure that Docker Engine and Docker Compose are installed. Before running for the first time do

```console
docker volume create --name=influxdb-volume
docker volume create --name=grafana-volume
```

To run the services

```console
docker-compose up -d
```
