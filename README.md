# Docker Node MongoDB Example

 Simple example of a dockerized Node/Mongo app

## Quick Start

```bash

# Install ansible roles
ansible-galaxy install -r requirements.yml

# Run using ansible
ansible-playbook playbook.yml
# OR
# Run in Docker
docker-compose up
# use -d flag to run in background

# Tear down
docker-compose down

# To re-build
docker-compose build
```
