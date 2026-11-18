# Practical 5 – Docker


## 1. Check Docker Version
wsl --install
```powershell
docker --version
docker compose version
docker run hello-world
docker pull nginx
docker run -d -p 8081:80 --name mynginx nginx

basic code 
docker images
docker ps
docker ps -a
docker stop mynginx
docker start mynginx
docker logs mynginx
docker rm -f mynginx
