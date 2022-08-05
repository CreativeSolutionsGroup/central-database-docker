```
#.env
MONGODB_ADDR=
```

All you need to do is run `docker compose up`.

Note that docker compose does not have a dash between it. In newer versions of docker, it is built into the docker binary.

This will start the mongodb docker container and the postgresql docker container. If you need more databases, please add them to the docker compose and then run `docker compose up`.