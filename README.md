# Dockerized Grafana (with InfluxDb and Telegraf backend)

to start (from cloned directory): `docker-compose up`
to stop: `docker-compose down`

fire StatsD UDP metrics at:
`127.0.0.1:8125`

access Grafana UI at:
`127.0.0.1:3000`

state will be stored in attached Docker volumes
