use your docker hub login name instead of `cloudgenius`

```
docker build -t cloudgenius/wordpress:6.4.3   .

docker login

docker push cloudgenius/wordpress:6.4.3
```
