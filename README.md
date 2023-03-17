awesome\_mail
=============

📧 Send mail with random motivational qoute or joke at spesific days during the week to your team.

Requirements
------------

[Community General](https://galaxy.ansible.com/community/general)

Role Variables
--------------

- awesome\_mail\_secure
- awesome\_mail\_port
- awesome\_mail\_host
- awesome\_mail\_from
- awesome\_mail\_to
- awesome\_mail\_cron\_hour
- awesome\_mail\_cron\_minute
- awesome\_mail\_random\_quote

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
