# example/echo:latest

## Cloning a repository

```
$ git clone https://github.com/mkssoo/Docker-practice.git
$ cd 20200217/
```

## The docker images build

```
$ docker image build -t example/echo:latest .
```

## Port forwarding and the container run

```
$ docker container run -d -p 10000:8080 example/echo:latest
```

```
$ curl http://localhost:10000/
Hello Docker!!
```
