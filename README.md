# Redis

- Redis version 4.0.14-alpine

## Build

```sh

docker build -t my-redis:0.0.1 .

```

## Run

```sh

docker run -d -it -p 6379:6379 my-redis:0.0.1

```
## Connect From Tool

Install `Redis Desktop Manager` from [here](https://snapcraft.io/redis-desktop-manager).
And connect with the configuration below and create a database.


```
host=localhost
port=6379
```

## Connect From App

```

hostname: "localhost"
port: 6379

```
