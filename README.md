# Atlassian Software - Docker Compose + Activate
Crack Atlassians plugins & Atlassian software as docker container

 
## Run Application

- Install Docker and Docker-compose.
- Clone this Project
- Run Compose File.
- Done!

### Jira Software Data Center
run [jira-compose.yml](/jira-compose.yml)

```bash
docker-compose -f jira-compose.yml up -d
```
> Use `http://<ip>:8080`

### Confluence Server

run [confluence-compose.yml](/confluence-compose.yml)

```bash
docker-compose -f confluence-compose.yml up -d
```
> Use `http://<ip>:8090`

### bitbucket Server

run [bitbucket-compose.yml](/bitbucket-compose.yml)

```bash
docker-compose -f confluence-compose.yml up -d
```
> Use `http://<ip>:8090`

### Bamboo Server

run [bamboo-compose.yml](/bamboo-compose.yml)

```bash
docker-compose -f bamboo-compose.yml up -d
```
> Use `http://<ip>:8085`

### Fisheye & Crucible 

run [fisheys-compose.yml](/fisheys-compose.yml)

```bash
docker-compose -f fisheys-compose.yml up -d
```
> Use `http://<ip>:8088`


### Jira Server Manegment (Service Desk)

run [servicemanagement-compose.yml](/servicemanagement-compose.yml)

```bash
docker-compose -f servicemanagement-compose.yml up -d
```
> Use `http://<ip>:8088`


## Activate (Crack) 

Moved Here : [activateAtlassianSoftware.md](activateAtlassianSoftware.md)


