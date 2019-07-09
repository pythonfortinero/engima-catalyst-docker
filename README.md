Engima catalyst docker image
======

# Build and run

1) build the project make

```
docker-compose build
```

2) run (automatically start a jupyer-notebook instance in 8000 port by default)

```
docker-compose up
```

see the docker log and copy this line

```
bot_1 | http://(b0d1ea2d301a or 127.0.0.1):8000/?token=b7b6a256b52915611fa358c9e09afdcc72d2fb7e508a0822
```
replace (b0d1ea2d301a or 127.0.0.1) for localhost and paste in the web browser


if you want run a command in the container

only you need run

```
docker-compose run bot <your-command>
```
