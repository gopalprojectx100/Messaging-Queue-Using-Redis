## Start Docker server

```bash
  docker run --name my-redis -d -p 6379:6379 redis
```

### Check if Docker is Running or not

```bash
  docker ps
```

### Connect to your docker container

```bash
  docker exec -it container_id /bin/bash
```

### Connect to your Redis CLI

```bash
  redis-cli
```

## Open two terminals
- Compile both backend and workers by using 

```bash
  tsc -b
```

- Go to backend folder and start backend by

```bash
  node dist/index.js
```

- Go to workers folder and start workers by

```bash
  node dist/index.js
```

