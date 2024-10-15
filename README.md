## DOCKER TP#2

# Etape 0
```docker container prune```
// close my eyes, prompt yes

# Etape 1
https://hub.docker.com/_/nginx

https://hub.docker.com/_/php/
https://github.com/docker-library/docs/blob/master/php/README.md#supported-tags-and-respective-dockerfile-links


`docker pull nginx:1.27`
`docker pull php:8.3-rc`

`docker container --detach --name http --publish 8080:80 nginx:1.27`
`docker container --detach --name php php:8.3-rc`


