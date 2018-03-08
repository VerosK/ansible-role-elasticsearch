VerosK.elasticsearch
==============

This role sets-up [elasticsearch][elasticsearch] on the target host. 

It's started as proof of concept but I've found myself to use it for more
than one year.


Role Variables
--------------

Please check `defaults/main.yml` 

Dependencies
------------

- geerlingguy.java


Example Playbook
----------------

    - hosts: elasticssearch
      roles:
         - role: VerosK.elasticsearch

License
-------

BSD-2 || WTFPL

Author Information
------------------

This role was prepared by Věroš Kaplan, sponsored by [teamguru][teamguru]

[teamguru]: https://www.teamguru.com/
[elasticsearch]: https://en.wikipedia.org/wiki/Elasticsearch
