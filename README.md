Lighthouse Role
=========

Install Lighthouse

Requirements
------------

Tested on Centos 7

Role Variables
--------------

`defaults/main.yml`

|     Variables     |      Description      |                 Default                 |
| :---------------: | :-------------------: | :-------------------------------------: |
|  lighthouse_git   |    Lighthouse URL     | https://github.com/VKCOM/lighthouse.git |
| lighthouse_folder | Folder for Lighthouse |             /tmp/lighthouse             |



Dependencies
------------

No dependencies

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - lighthouse

License
-------

MIT

Author Information
------------------

Aleksei Iarin
