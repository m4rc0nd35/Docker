### Docker
- Login
```
docker login
```
- build image
```
docker build -t <account>/<image_name>:tag <path_build>
```
- tag image
```
docker tag <image_id> <account>/<image_name>:tag
```
- push image
```
docker push <account>/<image_name>:tag
```
- up docker
```
docker container run --name test -p 8080:8080 <account>/<image_name>:tag
````
