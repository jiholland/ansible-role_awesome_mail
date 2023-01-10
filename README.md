awesome\_mail
=============

📧 Send mail with random motivational qoute or joke at spesific days during the week to your team.

Requirements
------------

[Community General](https://galaxy.ansible.com/community/general)

Role Variables
--------------

- mail\_secure
- mail\_port
- mail\_host
- mail\_from
- mail\_to
- cron\_hour
- cron\_minute

Dependencies
------------

None.

Example Playbook
----------------

    ---
    - name: Mail awesomeness to your crew
      hosts: localhost
      gather_facts: true

      roles:
         - awesome_mail

📅 Use tag **schedule** to schedule using cron.

License
-------

BSD

Author Information
------------------

Jørn Ivar Holland
