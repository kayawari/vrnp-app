# Setting

```sh
cp .env.sample .env

docker compose build
docker compose up # TODO: 要修正

docker compose exec front sh -c "yarn create vite <FRONT_PROJ_NAME> --template react-ts"
docker-compose exec api sh -c "nest new <API_PROJ_NAME> --package-manager yarn --skip-install --skip-git"

docker compose down
docker compose up
```

ref: [React(TypeScript) × NestJS × PostgreSQL × docker-compose開発環境　個人的ベストプラクティス](https://qiita.com/katkatprog/items/a53fa97ba60fa361983a)