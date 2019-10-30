# docker-flask-hello-world

Docker is powerful. Docker has a learning curve. Docker is a giant whale with a shipping container backpack. Start off small and build up with the simplest flask app you can make with docker! This example walks through setting up a dockerfile, organizing your container and packaing your app. Good luck!

## Build...
From the directory containing this `Dockerfile` run:
```
docker build --tag image-name .
```

## Run...
```
docker run -d -p 8001:8000 --name container-name image-name
```
