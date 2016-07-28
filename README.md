# hello-docker-compose

### Quick Start

```sh
ln -s ./docker-compose.override.yml.sample ./docker-compose.override.yml
ln -s ./.env.web.sample ./.env.web
docker-compose run --rm web bin/rails db:create db:migrate

# Use --service-ports option to enable debugging with binding.pry
docker-compose run --rm --service-ports web

# open localhost:3000
```
