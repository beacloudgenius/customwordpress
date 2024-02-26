use your docker hub login name instead of `cloudgenius`

```
git clone https://github.com/beacloudgenius/customwordpress.git

cd customwordpress/custom-image

docker build -t cloudgenius/wordpress:6.4.3   .

docker login

docker push cloudgenius/wordpress:6.4.3

cd ..
```
