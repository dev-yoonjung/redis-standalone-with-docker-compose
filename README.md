# Run

```
docker-compose -f {path} up -d
```

- `up` Create and start containers
- `-f` Specify the name and path of one or more compose files
- `-d` Process in the background

# Use redis-cli

```
docker exec -it standalone-redis redis-cli

auth password
```

<img width="586" alt="스크린샷 2023-04-17 오전 9 22 59" src="https://user-images.githubusercontent.com/98807166/232352439-e273d4c3-f870-4781-99e8-d3fd7592adf6.png">

# Stop

```
docker-compose -f {path} down
```
