# wordpress-docker
## Template for Installing and deploying WordPress website with Nginx, SSL self-signed , MySQL DB inside a Docker container.  Tested on *Debian




## Installation

- Clone the repository
```
https://github.com/dstf/wordpress-docker.git
```

- Change the $domain inside the file named:
```
./nginx./default.conf
```
- Install Docker Compose 
```
apt install docker-compose
```
- Run the enviroment
```
docker-compose build
```
```
docker-compose up -d
```
