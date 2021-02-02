# demo-nextjs-docker

## docker-compose up まで

```
$ docker-compose run --rm next npm install create-next-app
$ vim .gitignore (/node_modulesを追加)
$ docker-compose run --rm next npx create-next-app demo-app
$ docker-compose up
```
