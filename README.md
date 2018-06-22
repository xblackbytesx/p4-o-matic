## A one-command self-hosted cloud/suite

- Requires Ansible 1.2 or newer
- Expects Debian Stretch 9.x hosts

Then run the playbook, like this:

	ansible-playbook -i hosts playbook.yml

The playbooks will configure MariaDB, Nginx, and PHP-FPM.

### Fully testable in a Virtual Machine:
Ensure you have the following software installed on your host system:
- Virtualbox
- Vagrant

#### Easy-access links for Vagrant testing:
https://p4.box:4430  

Example `/etc/hosts` file:
```
127.0.0.1 p4.box
```
