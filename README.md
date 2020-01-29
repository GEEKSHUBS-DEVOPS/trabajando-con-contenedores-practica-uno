![](https://github.com/GEEKSHUBS-DEVOPS2020/trabajando-con-contenedores/blob/master/logo.png?raw=true)

# Practice-one

Microservices a y b project 

In this project, microservice-a and microservice-b makes a solution for practice 2 chalenge, this services needs mongo db, redis and minio provides in this repository under docker technology

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Prerequisites

You need docker and docker comopose founds in your host environment, you can virtualize using vagrant or another system

https://docs.docker.com/compose/install/

You must be a capacity for execute bash scripts. ( under windows you can install cygwin console or similars )


### Installing

* clone this repository



* launch scripts for install vendors in source parts

```
./bin/npm-microservice-a install
./bin/npm-microservice-b install
```

* lauch this for start project

```
./bin/start
```

* this execute service in background, if you break execution all services will be continue in run


* with this script you can reconect to logs output
```
./bin/logs
```

* this script cleanup all system

```
./bin/cleanup
```


## Scripting



use loopback4 cli inside microservice containers
```
./bin/lb4-microservice-a

./bin/lb4-microservice-b
```

run npm inside microservice containers
```
./bin/npm-microservice-a

./bin/npm-microservice-b
```


this script run lb4-cli for start new loopback4 project inside source folder
```
./bin/lb4-source-starter
```




## Authors

* **David Pestana**

## License

