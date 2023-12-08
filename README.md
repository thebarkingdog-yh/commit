# for Developer (Poetry)
## 安裝 Poetry

```shell
curl -sSL https://install.python-poetry.org | python3 -
```

## 安裝或同步套件

```shell
poetry install
```

## Run server

```shell
python3 run.py
```

## for Deployment (Docker)

## build image

```shell
docker build -t tbd_langchain_img .
```

## run server

```shell
docker run --name tbd_langchain -it -p 9736:9736 tbd_langchain_img
```

[//]: # (## run server)

[//]: # (```sheel)

[//]: # (docker compose up -d --build)

[//]: # (docker compose up --build)

[//]: # (docker compose up)

[//]: # (```)

### docker-compose

```
docker-compose up -d --build
docker-compose restart app
docker-compose logs -f app
```
