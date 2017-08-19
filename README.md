# Ansible-Nginx

[![Build Status](https://travis-ci.org/k0st1an/ansible-nginx.svg?branch=master)](https://travis-ci.org/k0st1an/ansible-nginx) [![Ansible Galaxy](https://img.shields.io/badge/galaxy-k0st1an.nginx-blue.svg?style=flat)](https://galaxy.ansible.com/k0st1an/nginx/)


Ansible role for deploing latest version Nginx


Tags:

- `nginx-conf` - to update `/etc/nginx/nginx.conf`


## Example Playbook

    - hosts: localhost
      remote_user: root
      roles:
         - k0st1an.nginx

## License

Apache license v2


## Author Information

- Author: Konstantin Kruglov
- GitHub: https://github.com/k0st1an
- Contact: kruglovk@gmain.com
