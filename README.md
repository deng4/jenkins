# jenkins
# Repo where you could find Dockerfile and compose file for building and running Jenkins in fomat of Docker container

To install docker pleae run:

curl -fsSL https://get.docker.com -o get-docker.sh
chmod +x ./get-docker.sh
./get-docker.sh

To run jenkins in a Docker with docker agent:

docker compose up -d

# docker-compose up -d in case you AWS Linux or any other Linux distro with yum.
