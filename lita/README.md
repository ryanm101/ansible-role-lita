Ansible Role: lita-slack
=========

An Ansible role that installs Lita & the lita-slack adaptor

Requirements
------------

- Slack Token

Role Variables
--------------

    lita_user: lita
    lita_group: lita
    lita_name: Lita
    lita_home: /srv/litabot
    lita_slack_token: xxx-000011112222333344445555XXX
    redis_srv: 127.0.0.1
    redis_port: 6379


Dependencies
------------

 - redis

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: ryanm101.lita }

License
-------

MIT

Author Information
------------------

http://ninet.org
