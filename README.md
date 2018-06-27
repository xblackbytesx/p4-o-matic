## A one-command P4 dev setup

- Requires Ansible 1.2 or newer
- Expects Debian Stretch 9.x hosts

The playbooks will configure MariaDB, Nginx, and PHP-FPM.

Ensure you have the following software installed on your host system:
- Virtualbox
- Vagrant
- Ansible

#### Firing up the Planet4 dev environment:
After cloning this repo go into it's root dir and execute the following:
```
vagrant up
```
Then wait a couple of minutes...
Aaanndd... PROFIT!

#### Local client host file addition:
In order to make the routing work a hostfile change is needed.
If you're smart (and you know you are) you make these changes whilst waiting for the provisioning to finish.
Here is an example `/etc/hosts` file:
```
127.0.0.1 p4.box
```

#### Easy-access links:
https://p4.box:4430  
