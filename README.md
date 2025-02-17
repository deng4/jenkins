# jenkins
# Repo where you could find Dockerfile and compose file for building and running Jenkins in fomat of Docker container

To install docker pleae run:

```bash
curl -fsSL https://get.docker.com -o get-docker.sh
chmod +x ./get-docker.sh
./get-docker.sh
sudo apt-get install -y uidmap
dockerd-rootless-setuptool.sh install
```


To run jenkins in a Docker with docker agent:
```bash
docker compose up -d
```

in case you AWS Linux or any other Linux distro with yum pacakge manager: docker-compose up -d 
