Dockerfile for Angular

## Abou Angular

See [Angular](https://angular.io/)

## Usage

Build and attach,

```shell
$ docker-compose -f "docker-compose.yml" up -d --build
$ docker exec -it angular_container /bin/sh
```

And create project use angular cli.

```shell
$ ng new app-name --directory ./ --style=sass
```

Have a good Angular life:)
