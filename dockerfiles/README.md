README
===========
for run this dockerfile follow the next steps
into to folder dockerfile execute the next commands 
```sh
$ docker build -t apache:1.0 .
```

next, we find our image apache:1.0
```sh
$ docker images
```
and now, we can start our container
```sh
$ docker run -p 80:80 --name servidor_web apache:1.0
```
and check in your browser
http://locahost
