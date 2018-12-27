# sample-docker-vue-cli3

- Qiita
[Dockerを使ってVue CLI 3 の開発環境を構築する](https://qiita.com/satokibi/items/189945f984e5e53117ea)

## Requirement
- Docker

## Usage

```shell
$ git clone https://github.com/satokibi/sample-docker-vue-cli3.git
$ cd sample-docker-vue-cli3
$ docker-compose up -d --build
$ docker-compose exec web /bin/ash
```

```terminal:コンテナ内
/app # vue create vue-project
/app/vue-project # cd vue-project
/app/vue-project # npm run serve
```

http://localhost:1234

