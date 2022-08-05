## Deployment

Write the `.env` file as defined in the [Config](#config) section.

Note that docker compose does not have a dash between it. In newer versions of docker, it is built into the docker binary.

This will start the mongodb docker container and the postgresql docker container. If you need more databases, please add them to the docker compose and then run `docker compose up`.

## Config

```
#.env
MONGODB_ADDR=
MONGODB_ROOT_PASSWORD=
POSTGRES_ROOT_PASSWORD=
```

## Ports

Wherever you are deploying this, some ports need to be exposed.

- 27017
- 5432 
- 10005
- 10006
- Optionally: 22

