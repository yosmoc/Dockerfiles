# React app development environment

## Build

```
docker build -t reactapp .
```

## Run

```
docker run -it /path/to/app:/app -p "3000:3000" reactapp bash
```