# docker-sqlserver

docker-sqlserver

## images

```
wachira90/sqlserver:2022-CU6-ubuntu-20.04
wachira90/sqlserver:2019-CU21-ubuntu-20.04
wachira90/sqlserver:2017-CU29-ubuntu-16.04
```

## docker images at

```sh
git clone https://github.com/wachira90/docker-sqlserver2019
cd docker-sqlserver2019/
```
## start first time

```sh
mkdir data/
sudo chmod -R 0777 data/
docker-compose up -d
```

## stop start

```sh
docker-compose stop
docker-compose start
```

## repo 

https://hub.docker.com/r/wachira90/sqlserver
