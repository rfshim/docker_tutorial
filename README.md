# Client for docker workshop

## Docker build

```
docker build --force-rm=true -t rfshim/docker-tutorial:1 .
```

## Docker run

```
docker run --rm -p 4567:4567 rfshim/docker-tutorial-app:1
```

## Test

```
ENDPOINT=https://workshop-docker-kr.herokuapp.com/ PARAM_NAME=rfshim PARAM_VERSION=2 PARAM_MESSAGE=message bundle exec ruby app.rb
```
