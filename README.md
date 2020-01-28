# React + Docker muiti-stage build example

This is a project created based on the article "[React in Docker with Nginx, built with multi-stage Docker builds, including testing](https://medium.com/@tiangolo/react-in-docker-with-nginx-built-with-multi-stage-docker-builds-including-testing-8cc49d6ec305)" by Sebastián Ramírez

## How to run
First build your image and tag it with a name:
```
docker build -t <your-tag-name> .
```

And you can run with:
```
docker run -p 80:80 <your-tag-name>
```