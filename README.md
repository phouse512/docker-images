## docker-images

Home of all of my docker images, used as bases for various other projects.

- ci-base: base image used in continuous integration that has common
    dependencies all included


### development

```
# build docker image
$ docker build -t phouse512/ci-base:0.0.0 ci-base/

# run a docker image just built
$ docker run -it phouse512/ci-base:x.x.x
```

