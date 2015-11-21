OpenWGA Ansible Role
=========

Installs OpenWGA.

Requirements
------------

This role only works with Debian and Ubuntu for now, because it uses the apt source provided by Innovationgate.

Role Variables
--------------

- openwga_config: Config XML, will replace the default, default none
- openwga_auth: Auth XML, default none
- openwga_version: Version to install, default 7.1
- openwga_edition: Edition to install, default ce

Dependencies
------------

Requires the Galaxy roles specified in requirements.yml. Install via

    ansible-galaxy install -r requirements.yml

Example Playbook
----------------

Check the example directory for example usage via Vagrant.

License
-------

MIT
