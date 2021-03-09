# facp-devops
facp-devops

docker build -t facp/node-web-app .

docker run -p 5000:5000 -d facp/node-web-app

docker logs 377cc00eea0e87c0847d39930fccbc9fe03b4bf1dad5
4d2509ce781bc4c5624a

docker exec -it 377cc00eea0e87c0847d39930fccbc9fe03b4bf1dad54d2509ce781bc4c5624a /bin/bash

curl -i localhost:49160
