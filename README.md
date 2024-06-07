Role Name
=========

Lighthouse role

Requirements
------------

Using https://github.com/VKCOM/lighthouse.git

Role Variables
--------------

server_name: Server DNS name.
nginx_config_path: Path to output config for nginx.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
        - role: lighthouse-role
          vars: 
            server_name: localhost
            nginx_config_path: /etc/nginx/conf.d/lighthouse.conf

License
-------

MIT

Author Information
------------------

Spasman
