# Asterisk ARI dockerized documentation
ARI for Asterisk 19.0.0
## How to start?
Run container
```
docker run --name ari-doc-nginx -d -p 8088:80 lold/ari-doc-nginx
```
Documentation served by [nginx](http://nginx.org/) with [Swagger UI](https://swagger.io/) [2.2.10](https://github.com/swagger-api/swagger-ui/tree/v2.2.10) on
```
http://localhost:8088/
```
