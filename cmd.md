### Найти и завершить процесс занимающий определенный порт
#### Windows

``` cmd
netstat -nao | find "9092"
```

``` cmd
taskkill /F /PID 50896
```

#### Linux

``` cmd
netstat -na | grep "9092"
```

``` cmd
kill -9 50896
```

docker-compose

```
docker compose --env-file .env.example -f docker-compose.yml config
docker compose --env-file .env.example -f docker-compose.yml up -d
```
