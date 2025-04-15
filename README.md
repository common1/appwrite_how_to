# appwrite_how_to

## See also

[https://appwrite.io/docs/advanced/self-hosting]

## docker

```
Stop all containers
$ docker stop $(docker ps -a -q)

Remove all containers
$ docker rm $(docker ps -a -q)

Delete all images
$ docker rmi -f $(docker images -aq)

```

## Start

```
$ docker compose up -d --remove-orphans
```

## Stop

```
$ docker compose stop

```
## Uninstall

```
$ docker compose down -v
```

