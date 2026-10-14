# OpenCode - AI агент

https://opencode.ai/v2/docs/

### Запуск контейнера
```shell
docker compose up -d
```
### Посмотреть в логах контейнера пароль для входа в UI
```shell
docker compose logs opencode
```

### Остановка и удаление контейнера
```shell
docker compose down -v
```

### Рестарт после изменения конфигурации opencode.json
```shell
docker compose restart opencode
```

### OpenCode UI
http://localhost:4096/