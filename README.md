docker build -t app:1.0 .
docker images
docker ps
docker stop <container_id>
docker exec -it <container_id> bash
docker run -d -p 3000:8099 app:1.0
//3000 is the local while 8099 is the port configured for spring boot app running in container
