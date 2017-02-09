ansible-role-apache-maven
=========

Simple role to download Apache Maven and add it to system wide PATH


Role Variables
--------------

```
apache_maven_version: 3.3.9
apache_maven_src_file_md5: e7ebd0b8d6811b42a5dad91fb27fe9b4
```


Dependencies
-------------

`Java`


Example Playbook
----------------

```
- hosts: loc-dev
  roles:
   - apache-maven
```


License
-------

MIT


Author Information
------------------

tal@pjili.org
