## Download image
docker pull ubuntu

## Start Container 
docker run ubuntu

## Start Container with terminal
docker run -it ubuntu

## Copy to container
docker cp foo.txt container_id:/foo.txt

## Copy from container
docker cp container_id:/foo.txt foo.txt

## List containers
docker container ls