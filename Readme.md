## Nginx

```commandline
docker build -t nginx .

```

Run below command to run the nginx docker container

```commandline
docker run --name nginx -p 8080:8080 nginx
```

```commandline
docker container ps -a
docker container stop <container-id>
docker container rm <container-id>
```