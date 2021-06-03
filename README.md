# FastAPI-Trafefik

Fast-API with traefik with docker
REQUIREMENTS:

- [FAST-API](https://fastapi.tiangolo.com/)
- [DOCKER](https://docs.docker.com/engine/install/ubuntu/)[]
- [DOCKER COMPOSE](https://docs.docker.com/compose/install)
- [TRAEFIK](https://github.com/traefik/traefik)

SETUP

- clone the project

RUN:

```
poetry install #or
pip install -r requirements.txt

docker-compose up -d --build
docker-compose up
```

Traefik Dashboard: http://fastapi.localhost:8080/
