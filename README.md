# try_docker_rails

## Setup

```sh
$ docker-compose up -d

$ docker-compose run --rm web bundle exec rake db:create
$ docker-compose run --rm web bundle exec rake db:migrate
# or
$ docker-compose exec web bundle exec rake db:create
$ docker-compose exec web bundle exec rake db:migrate
```

## Start

```sh
$ docker-compose start
```

## Stop

```sh
$ docker-compose stop
```

## Delete(Cleaning)

```sh
$ docker-compose down
```

## View output from containers

```sh
$ docker-compose logs -f
```
