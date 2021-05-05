# DevOps Infra

## Run Docker Compose
```
docker-compose up -d
```
### Gitea

is running in `http://localhost:3000`.

### Jenkins

is running in `http://localhost:8081`.

> Firs Log in
> View the generated administrator password to log in the first time.

`docker exec jenkins cat /var/jenkins_home/secrets/initialAdminPassword`

### Sonarqube

is running in `http://localhost:9000`.

### Nexus

> First Admin Password

``docker exec nexus cat /nexus-data/admin.password``

is running in `http://localhost:10680/`.
