# mypost-ui-ngx

A _Docker_ container for MyPost Consumer _Angular 4_ frontend apps.

Created for internal use; extends the `mypost-ui-base` container.

Includes:
```
node 8.0.0 / npm 5.0.0
yarn
gyp
node-gyp
@angular/cli
```

To build a default container from the `Dockerfile` run:
```
docker build -t benboarder/mypost-ui-ngx:latest .
```

To build a container using a specific version of _ng-cli_ from the `Dockerfile` run:
```
docker build {--build-arg NG_CLI_VERSION=1.6.6} -t mypost-ui-ngx .
```

To use the latest version run:
```
docker pull benboarder:mypost-ui-ngx
```
