mail\_awesomeness
=================

🙌 Send mail with random motivational qoute or joke at spesific days during the week to your crew.

Requirements
------------

[Community General](https://galaxy.ansible.com/community/general)

Role Variables
--------------

defaults/main.yml:
- mail\_secure
- mail\_port
- mail\_host
- mail\_from
- mail\_to

vars/main.yml:
- random\_quotes
- boost\_list
- wisdom\_list
- fun\_list

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
         - mail_awesomeness

License
-------

BSD

Author Information
------------------

Jørn Ivar Holland
