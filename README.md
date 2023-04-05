# GOGS через docker-compose

### Запуск локальной системы контроля версий в docker-контейнере

---

### Процесс запуска
1. Установите [Docker](https://www.docker.com/)
2. Склонируйте этот репозиторий
3. Создайте файл ```.env``` со следующим содержимым:
```shell
    PG_DATABASE=gogs_db
    PG_USER=gogs_user
    PG_PASSWORD=gogs_password
```
4. Запустите контейнер командой ```docker compose up -d```
