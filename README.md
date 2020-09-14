# cursodocker-website
Sitio web de ejemplo utilizado en el curso de Docker

## To psuh an image on the hub.docker
### First we have to create a tag for are image
docker tag my-website rzaragozasolis/my-web

### Login to doker hub
docker login

#### Username rzaragozasolis

## Once login we have ti push the image
docker push rzaragozasolis/my-web

### Pull the image already push
#### https://hub.docker.com/repository/docker/rzaragozasolis/my-web/tags?page=1
docker pull rzaragozasolis/my-web:latest
