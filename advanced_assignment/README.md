# Advanced assignment

This assignment is a solution for [Advanced assignment](https://robertdebock.nl/learn-ansible/ADVANCED/advanced_assignment).


## Docker compose

This solution uses `docker-compose` to create the infrastructure. Using Docker is not required, but it makes it easier to setup the infrastructure. Hava a look in the `infrastructure` directory for more information.

In order to allow Ansible to connect to the containers, please install a collection:

```bash
ansible-galaxy install -r requirements.yml
```
