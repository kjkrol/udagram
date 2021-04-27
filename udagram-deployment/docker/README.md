Build the images: 

```
docker-compose -f docker-compose-build.yaml build --parallel
```

Push the images: 

```
docker-compose -f docker-compose-build.yaml push
```

Run the container: 

```
docker-compose up
```