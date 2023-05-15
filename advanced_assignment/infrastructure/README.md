# Docker Compose

This directory contains the docker-compose file for the infrastructure of the project. It will create:

- Two webserververs
- Two databaseservers

## Usage

To start the infrastructure, run the following command:

```bash
docker-compose up --detach
```

Add the names of the created containers to you inventory:

```ini
[webservers]
infrastructure-node-1-1 ansible_connection=docker
infrastructure-node-2-1 ansible_connection=docker

[databaseservers]
infrastructure-node-3-1 ansible_connection=docker
infrastructure-node-4-1 ansible_connection=docker

[production]
infrastructure-node-[1:3:2]-1

[development]
infrastrucutre-node-[2:4:2]-1
```
