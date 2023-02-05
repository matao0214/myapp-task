## README
reference1: https://qiita.com/suzuko24/items/3876cfb6ada3e3111b3c
reference2: https://zenn.dev/hayatoomori/articles/83880221350f7e

## Pushing image
$ docker tag 43de5fd86158 gcr.io/decisive-cinema-280910/myapp-resume-app:latest
$ docker push gcr.io/decisive-cinema-280910/myapp-resume-app:latest

## deploy to production
docker build -t react-app:nginx -f Dockerfile.prod .

https://qiita.com/kudota/items/6eb030cbabaa591c043d
https://qiita.com/huntas0624/items/aaea49f66973698e311d


