## Dockerizing Flask With Compose and Machine

Disease-area is a tool to show hospitals and disease area of poplutation on a map

Featuring:

- Docker v1.12.2
- Docker Compose 1.7.1, build 6c29830 
- Docker Machine v0.8.1 

## How to run

SQLite is used during developing.
If the db isn't exist - flask-sqlalchemy initializes it automatically from the model.
```
docker compose up -d
```

```
<vm_ip>:80 - nginx 
<vm_ip>:8080 - application
```
