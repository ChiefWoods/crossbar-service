# Crossbar Service

Docker container for running a Crossbar instance to store jobs and fetch Switchboard feeds.

## Setup

Build and run the Docker container:

```sh
docker-compose up -d
```

Check the status of the container:

```sh
docker-compose ps
```

Stop the container:

```sh
docker-compose down
```

Restart the container:

```sh
docker-compose up -d
```

View logs of the running container:

```sh
docker-compose logs -f
```