### Setup WordPress
```
$ docker-machine create --driver virtualbox <MachineName>
$ eval $(docker-machine env <MachineName>)
$ docker-compose build
$ docker-compose up -d
$ open "http://$(docker-machine ip <MachineNam>)"
```
