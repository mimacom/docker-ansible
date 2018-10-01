# Ansible

This image contains ansible, which you can use for example to set up a
deployment/delivery pipeline using docker.

Use tags to specify what ansible version you want to use.

# Example usage
docker run -ti -v "$(pwd)":/media/docker --name ansible --rm
mimacom/ansible:latest
