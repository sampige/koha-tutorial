Libreoffice Tutorials Image
============================

#### Building an image
```
$ docker build -t sampige-koha-tutorial .
```

#### Running the container
```
$ docker run --name s-koha-tutorial -p 8080:80 -d sampige-koha-tutorial
```

### Stopping the container
```
$ docker stop s-koha-tutorial
```
