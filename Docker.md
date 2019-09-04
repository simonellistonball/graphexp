# Running GraphExp quickly in Docker

Simple Nginx based hosting.

```
docker build . -t some-tag
docker run -d -p 8080:80 --name graphexp some-tag
```