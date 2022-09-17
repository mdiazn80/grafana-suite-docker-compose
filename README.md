# grafana-suite-docker-compose

## Requirements

 - https://www.docker.com/

## Install

### Init

Start All
```
$ docker compose up -d
```

Start Modules:

```
$ docker compose up -d prometheus
$ docker compose up -d alertmanager
$ docker compose up -d nodeexporter
$ docker compose up -d grafana
```

Stop
```
$ docker compose stop
```

## Documentation
* https://docs.docker.com/
* https://grafana.com/docs/
