# Dockerfile for jupyter notebook

## Build image

```
docker build -t jupyter .
```

## Run container

```
docker run -d -p 8888:8888 -v /path/to/notebooks:/notebooks jupyter
```

## Stop container

```
docker stop container_name
```