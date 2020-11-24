basic docker commands

sudo docker build -t name/name:version .
sudo docker run -p port:5510 dockerimage_id

when container is running:
sudo docker container ls
sudo docker exec -it container_id bash

when app is stopped, we wont be able to see container