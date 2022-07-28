# jenkins-installon on linux
## Create a docker image
```
docker login
docker build -t digupats/devsecops -f Dockerfile .
```

## Create a docker compose file
## Start container
```
docker-compose up -d
```
## How to check password of jenkins
```
docker exec <container> cat /var/jenkins_home/secrets/initialAdminPassword
```

# jenkins-installon on windows 

Follow this [Installation guide](https://www.youtube.com/watch?v=XuMrEDA8cAI)
